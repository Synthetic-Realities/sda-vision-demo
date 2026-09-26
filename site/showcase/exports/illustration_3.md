# SDA Vision analysis

- **File:** illustration-3.webp
- **Tool version:** 0.1.0
- **Verdict:** authentic likely (confidence medium)
- **Indicative score:** 5/100 (median of available model ratings; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** 17442d095e61a319e806d0a58993fcb5b4a89705867bda5ead74b82bec4b8add
- **Headline:** Leaning authentic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T18:37:51+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Recomputed locally from saved LLM replies acquired at 2026-09-25T11:22:07+00:00 under method publication-repair-2026-09-24.3. Original report ae05de4f-1d78-4c71-85a5-9a9e833d7306 is preserved. No new provider requests. The original analysis used a source-labelled filename; this is not a source-blind comparison.
- Presentation copy of saved report a7209748-4dcd-4092-898a-e2a5dc6c475f. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | authentic likely | 5 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | authentic likely | 5 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 25 | high | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Consistent hand-drawn ink linework with natural stroke weight variation
  - Cross-hatched shading at left edge typical of manual/digital-pen editorial cartooning
  - Coherent, correctly spelled hand-lettered text in speech bubble and labels
  - Legible artist signature ('BEELER') with year mark
  - Legible syndicate/publication credit ('The Columbus Dispatch', 'CagleCartoons.com')
- **OpenAI Vision**:
  - Consistent pen-and-ink outlines and crosshatched shading throughout the cartoon
  - Coherent, legible hand-lettered speech and disease labels
  - Deliberate caricature proportions and integrated symbolic virus heads
  - Visible publication credit and artist signature
  - Caveat: Appears to be a conventional editorial illustration, not a camera photo; visual inspection alone cannot verify authorship or exclude AI edits, and the stylized signature/date are difficult to read.
- **Gemini Vision**:
  - Consistent editorial cartoon linework
  - Artist signature and syndication text
  - Hand-drawn hatching and crosshatching
  - Coherent hand lettering
  - Caveat: Editorial illustrations follow stylistic conventions distinct from photographic media, which automated detectors may mischaracterize.
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

- **Claude Vision** (5): synthetic likelihood 5/100; tells: consistent hand-drawn ink linework with natural stroke weight variation, cross-hatched shading at left edge typical of manual/digital-pen editorial cartooning, coherent, correctly spelled hand-lettered text in speech bubble and labels, legible artist signature ('BEELER') with year mark
- **OpenAI Vision** (5): synthetic likelihood 5/100; tells: Consistent pen-and-ink outlines and crosshatched shading throughout the cartoon, Coherent, legible hand-lettered speech and disease labels, Deliberate caricature proportions and integrated symbolic virus heads, Visible publication credit and artist signature
- **Gemini Vision** (25): synthetic likelihood 25/100; tells: consistent editorial cartoon linework, artist signature and syndication text, hand-drawn hatching and crosshatching, coherent hand lettering

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
I REJECT VACCINES OUT OF LOVE FOR MY CHILDREN. | VAX | MEASLES | MUMPS | RUBELLA | THE COLUMBUS DISPATCH CAGLECARTOONS.com | BEELER ©19
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=[]; authentic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=authentic_likely; confidence=medium; reason=3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.
