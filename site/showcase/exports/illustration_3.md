# SDA Vision analysis

- **File:** illustration-3.webp
- **Tool version:** 0.1.0
- **Verdict:** authentic likely (confidence medium)
- **Indicative score:** 8/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** 17442d095e61a319e806d0a58993fcb5b4a89705867bda5ead74b82bec4b8add
- **Headline:** Leaning authentic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:04+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | authentic likely | 5 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | authentic likely | 8 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 25 | high | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Hand-drawn ink linework with consistent, deliberate pen strokes
  - Coherent, correctly spelled hand-lettered text in speech bubble and labels
  - Legible artist signature and syndication credit (The Columbus Dispatch / CagleCartoons.com, dated '19)
  - Cross-hatching texture on left background typical of traditional/digital-inked editorial cartoons
  - Anatomically coherent hands and consistent character styling
- **OpenAI Vision**:
  - Consistent editorial-cartoon ink outlines and crosshatching
  - Coherent hand-lettered speech and disease labels
  - Deliberate, consistent caricature proportions
  - Integrated publication credit and artist signature
  - No conspicuous generative texture or lettering artifacts
- **Gemini Vision**:
  - Consistent hand-drawn editorial cartoon style
  - Legible artist signature and syndicate attribution
  - Coherent crosshatching and ink work
  - Absence of diffusion generation artifacts
  - Caveat: Editorial illustrations are non-photographic, requiring human review to confirm original publication provenance.
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.3, peak 34 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 19.52 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 12.27 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (5): synthetic likelihood 5/100; tells: hand-drawn ink linework with consistent, deliberate pen strokes, coherent, correctly spelled hand-lettered text in speech bubble and labels, legible artist signature and syndication credit (The Columbus Dispatch / CagleCartoons.com, dated '19), cross-hatching texture on left background typical of traditional/digital-inked editorial cartoons
- **OpenAI Vision** (8): synthetic likelihood 8/100; tells: Consistent editorial-cartoon ink outlines and crosshatching, Coherent hand-lettered speech and disease labels, Deliberate, consistent caricature proportions, Integrated publication credit and artist signature
- **Gemini Vision** (25): synthetic likelihood 25/100; tells: consistent hand-drawn editorial cartoon style, legible artist signature and syndicate attribution, coherent crosshatching and ink work, absence of diffusion generation artifacts

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
THE COLUMBUS DISPATCH CAGLECARTOONS.COM Beeler 2019 / I REJECT VACCINES OUT OF LOVE FOR MY CHILDREN. / NO VAX / MEASLES / MUMPS / RUBELLA
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=[]; authentic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=authentic_likely; confidence=medium; reason=3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.
