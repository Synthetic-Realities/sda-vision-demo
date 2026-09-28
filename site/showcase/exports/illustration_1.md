# SDA Vision analysis

- **File:** illustration-1.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 78/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** 137f1b7c292c882be741e1a6c881ab4a2082c7dd6ab2181d63304000a0d92252
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:03+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software citation: Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: illustration-1.png; media type: image; recorded at: 2026-09-26T22:31:03+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 82 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 78 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Not a camera photo: digital illustration in a uniform, polished comic/ink-and-colour style typical of current image generators
  - Hyper-consistent line weight and cel shading across all figures with no stroke variation or construction marks
  - Noisy, fragmented texture in the grey curly hair, resembling generator detail artifacts rather than deliberate strokes
  - Tablet screen shows an indistinct garden/playground scene with smeared, non-specific detail
  - Wheelchair spokes and frame are mostly plausible but slightly irregular in spacing and junctions
- **OpenAI Vision**:
  - Older woman's gray hair contains tangled, ribbon-like shapes inconsistent with the other hair rendering.
  - Wheelchair spokes and lower frame tubes form irregular junctions and ambiguous connections.
  - Gesturing hands have uneven finger separation and merged-looking contours.
  - Tablet garden has noticeably softer, less defined detail than the surrounding outlined illustration.
  - Caveat: This is a digital illustration, not a photograph; stylized drawing errors alone cannot establish AI origin without provenance.
- **Gemini Vision**:
  - Stylized digital line art with subtle AI generative markers
  - Irregular finger proportions and geometry
  - Overly smooth shading gradients typical of generative models
  - Inconsistent perspective on wheelchair spokes
  - Caveat: High-quality human digital vector/raster illustrations often closely resemble generative 2D art styles.
- **C2PA Content Credentials**:
  - File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.
  - Credentials: embedded manifest found.
  - Integrity: valid (SDK validation).
  - Signer trust: untrusted under the configured verifier.
  - Active manifest: Manifest declares AI-generated content.
  - Claim generator (declared tool): OpenAI Media Service API
  - Declared signer: OpenAI OpCo, LLC
  - Declared source type: http://cv.iptc.org/newscodes/digitalsourcetype/trainedalgorithmicmedia
  - Active record - declared tool: OpenAI Media Service API; actions: c2pa.created, c2pa.converted, c2pa.watermarked.unbound.
  - Active record - all actions recorded (signer's declaration): no.
  - Validation outcome: signingCredential.untrusted
  - Validation outcome: timeStamp.validated
  - Validation outcome: claimSignature.insideValidity
  - Validation outcome: claimSignature.validated
  - Validation outcome: assertion.hashedURI.match
  - Validation outcome: assertion.dataHash.match
  - Validation outcome: timeStamp.untrusted
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.9, peak 96 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 11.51 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 21.99 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (82): synthetic likelihood 82/100; tells: not a camera photo: digital illustration in a uniform, polished comic/ink-and-colour style typical of current image generators, hyper-consistent line weight and cel shading across all figures with no stroke variation or construction marks, noisy, fragmented texture in the grey curly hair, resembling generator detail artifacts rather than deliberate strokes, tablet screen shows an indistinct garden/playground scene with smeared, non-specific detail
- **OpenAI Vision** (78): synthetic likelihood 78/100; tells: Older woman's gray hair contains tangled, ribbon-like shapes inconsistent with the other hair rendering., Wheelchair spokes and lower frame tubes form irregular junctions and ambiguous connections., Gesturing hands have uneven finger separation and merged-looking contours., Tablet garden has noticeably softer, less defined detail than the surrounding outlined illustration.
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: stylized digital line art with subtle AI generative markers, irregular finger proportions and geometry, overly smooth shading gradients typical of generative models, inconsistent perspective on wheelchair spokes

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
