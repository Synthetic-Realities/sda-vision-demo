# SDA Vision analysis

- **File:** illustration-2.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 82/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** 6693be931db5fb33a8cacfae382bf3bc79fc23b0d9f8e967015a663688d8c8f5
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:04+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software citation: Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: illustration-2.png; media type: image; recorded at: 2026-09-26T22:31:04+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 88 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 82 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Garbled secondary text on props: 'ULTRA-PATCAI' bottle label, 'Buy Chloe' / 'Buy' rendered as 'Buu' on placard, 'REMEDV' jar label
  - Illegible pseudo-text lines on 'VACCINE FACTS' sheet and 'REMEDY' label
  - 'EMERGENCY' sign truncated and awkwardly occluded
  - Uniform glossy semi-realistic comic rendering typical of diffusion image models across all faces
  - Man with megaphone holding a bottle in a hand of ambiguous ownership near the poster, suggesting limb/hand attribution confusion
- **OpenAI Vision**:
  - Ambiguous arm ownership around the megaphone and raised bottle
  - Cramped, irregular finger contours around the small ULTRA-PATCH bottle
  - Background placard repeats 'Chloe Dubois Buy Chloe' without clear layout logic
  - Highly uniform glossy facial shading and repeated stylized hair highlights across the crowd
  - Caveat: This is an illustration, not a camera photo; stylization and polished lettering alone cannot distinguish AI generation from human artwork. Source files and provenance need review.
- **Gemini Vision**:
  - Model read this as AI editing over a photographic base image
  - Smooth vector-comic diffusion styling
  - Slight anatomical and hand rendering anomalies
  - AI-typical illustrative shading on hair and faces
  - Typeset overlays added digitally over generated background art
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.4, peak 24 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 14.26 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 13.87 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (88): synthetic likelihood 88/100; tells: garbled secondary text on props: 'ULTRA-PATCAI' bottle label, 'Buy Chloe' / 'Buy' rendered as 'Buu' on placard, 'REMEDV' jar label, illegible pseudo-text lines on 'VACCINE FACTS' sheet and 'REMEDY' label, 'EMERGENCY' sign truncated and awkwardly occluded, uniform glossy semi-realistic comic rendering typical of diffusion image models across all faces
- **OpenAI Vision** (82): synthetic likelihood 82/100; tells: Ambiguous arm ownership around the megaphone and raised bottle, Cramped, irregular finger contours around the small ULTRA-PATCH bottle, Background placard repeats 'Chloe Dubois Buy Chloe' without clear layout logic, Highly uniform glossy facial shading and repeated stylized hair highlights across the crowd
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: model read this as AI editing over a photographic base image, smooth vector-comic diffusion styling, slight anatomical and hand rendering anomalies, AI-typical illustrative shading on hair and faces

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
Chloe Dubois is suffering “side effects”! Our unique detox patches are the ONLY answer! Buy them now! The true cure! | STOP YOUR DANGEROUS LIES! Chloe is healthy and pro-vaccine! Vaccines are proven safe! | The only “injury” is your grift! Our public health is not for sale. Science Defends All! | Chloe Dubois Buu Chloe | ULTRA-PATCAI | HOSPITAL | EMERGENCY | ULTRA-PATCH | CHLOE-CLEANSE | REMEDV | VACCINE FACTS | CHLOE DUBOIS | SDA
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
