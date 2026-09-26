# SDA Vision analysis

- **File:** illustration-1.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 78/100 (median of available model ratings; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** 137f1b7c292c882be741e1a6c881ab4a2082c7dd6ab2181d63304000a0d92252
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T17:54:47+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Recomputed locally from the same saved provider replies acquired under run five-examples-20260926-r1. No new provider requests. Original report 6ed01bd6-3868-4680-ba90-536492d5c7ff was generated at 2026-09-26T17:38:40+00:00 under method publication-repair-2026-09-24.3; that report is preserved.
- Method verdict-consistency-2026-09-26.1: directional model votes require matching explicit verdicts and rating thresholds. Inconclusive replies retain their ratings and remain undecided observations.
- Presentation copy of saved report 6faeca61-589d-4810-8b3a-aec00dfb18e5. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 85 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 78 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Uniform digital-illustration style with inked outlines and painterly shading typical of current image generators
  - Over-regular stippled texture in grey curly hair
  - Wheelchair spoke and frame geometry inconsistent between wheels, with spokes merging and fading
  - Tablet screen shows a generic, softly detailed garden scene with no UI elements
  - Hands plausible but slightly smoothed, with simplified finger joints
- **OpenAI Vision**:
  - Gray hair contains tangled, ribbon-like shapes inconsistent with the other hair rendering.
  - Wheelchair spokes and frame supports intersect in mechanically ambiguous ways.
  - Gesturing hands have uneven finger separation and awkward contours.
  - Illustrated outlines and smooth shading throughout; no photographic base is evident.
  - Caveat: This is a stylized illustration; human-drawn or stock artwork can share these irregularities, so source provenance should be checked.
- **Gemini Vision**:
  - Digital illustration style with hyper-clean lines
  - Typical diffusion model character rendering features
  - Slight anatomical inconsistencies in hands and fingers
  - Unusual blending around tablet screen integration
  - Caveat: Vector or digital human art can closely mimic generative cartoon styles.
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

- **Claude Vision** (85): synthetic likelihood 85/100; tells: uniform digital-illustration style with inked outlines and painterly shading typical of current image generators, over-regular stippled texture in grey curly hair, wheelchair spoke and frame geometry inconsistent between wheels, with spokes merging and fading, tablet screen shows a generic, softly detailed garden scene with no UI elements
- **OpenAI Vision** (78): synthetic likelihood 78/100; tells: Gray hair contains tangled, ribbon-like shapes inconsistent with the other hair rendering., Wheelchair spokes and frame supports intersect in mechanically ambiguous ways., Gesturing hands have uneven finger separation and awkward contours., Illustrated outlines and smooth shading throughout; no photographic base is evident.
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: digital illustration style with hyper-clean lines, typical diffusion model character rendering features, slight anatomical inconsistencies in hands and fingers, unusual blending around tablet screen integration

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
