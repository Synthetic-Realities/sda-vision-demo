# SDA Vision analysis

- **File:** journal-image.png
- **Tool version:** 0.1.0
- **Verdict:** inconclusive (confidence low)
- **Indicative score:** n/a (no numeric score)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** b11aa1e8c5c17a9496d362987bd4bf0c00a83bccd3a4a704f0f6ab7a7cf6fc8d
- **Headline:** Inconclusive
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T18:37:47+00:00
- **Models:** none

> No vision model returned a usable result. Check provider status in the table.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Local checks only. LLM visual checks have not been run for this example; no provider requests or fees. An Inconclusive combined result here reflects unavailable visual assessments, not three inconclusive model replies.
- Presentation copy of saved report 51daff64-c246-46da-95b5-06bef3c925b8. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | - | vision | disabled | inconclusive |  | - | - |
| OpenAI Vision | - | vision | disabled | inconclusive |  | - | - |
| Gemini Vision | - | vision | disabled | inconclusive |  | - | - |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - No request or image was sent to this provider for this record.
- **OpenAI Vision**:
  - No request or image was sent to this provider for this record.
- **Gemini Vision**:
  - No request or image was sent to this provider for this record.
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.8, peak 53 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 10.42 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 24.85 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- (none)

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=[]; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=inconclusive; confidence=low; reason=No vision model returned a usable result. Check provider status in the table.
