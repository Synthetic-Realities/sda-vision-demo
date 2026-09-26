# SDA Vision analysis

- **File:** animal-portrait.jpg
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 84/100 (median of available model ratings; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** bdc5c19d4211d9c9f9f8dce5bf4e4dec29e9b32e308ff12a60979481e928154f
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T18:37:49+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Recomputed locally from saved LLM replies acquired at 2026-09-25T09:04:42+00:00 under method publication-repair-2026-09-24.3. Original report b487ceee-de8a-4546-bdd2-1aa3066f0245 is preserved. No new provider requests. The original analysis used a source-labelled filename; this is not a source-blind comparison.
- Presentation copy of saved report c624f79c-a343-4aff-8450-3a4b7ded4d97. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 88 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 84 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 47 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Hat merges with head with no visible ears or straps; fold-like ear shapes sit ambiguously under brim
  - Overly smooth, idealized fur rendering with painterly micro-texture on face
  - Whiskers unusually long, dense and uniformly bright, some originating from implausible positions
  - Near-identical glossy eye reflections with slightly irregular pupil shapes
  - Hyper-stylized golden-hour backlight and creamy bokeh typical of text-to-image 'cinematic portrait' outputs
- **OpenAI Vision**:
  - Chest fur forms unusually broad, layered, feather-like clumps
  - Cheek fur has a densely etched, repetitive texture
  - Ear contours merge ambiguously with fur beneath the hat brim
  - Highly polished eye and nose surfaces contrast with exaggerated fur detail
  - Coherent warm rim lighting and background blur provide some photographic plausibility
- **Gemini Vision**:
  - Overly uniform airbrushed fur rendering
  - Implausible ear integration under hat
  - Perfect studio lighting and stylized depth of field blur
  - Caveat: High-quality digital rendering or retouching on real reference photos can mimic full synthesis.
- **C2PA Content Credentials**:
  - File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.
  - Credentials: embedded manifest found.
  - Integrity: valid (SDK validation).
  - Signer trust: untrusted under the configured verifier.
  - Active manifest: Manifest declares AI-generated content.
  - Claim generator (declared tool): Adobe_Firefly
  - Declared signer: Adobe Inc.
  - Declared source type: http://cv.iptc.org/newscodes/digitalsourcetype/trainedalgorithmicmedia
  - Active record - declared tool: Adobe_Firefly; actions: c2pa.created.
  - Active record - all actions recorded (signer's declaration): yes.
  - Validation outcome: signingCredential.untrusted
  - Validation outcome: timeStamp.validated
  - Validation outcome: timeStamp.trusted
  - Validation outcome: claimSignature.insideValidity
  - Validation outcome: claimSignature.validated
  - Validation outcome: assertion.hashedURI.match
  - Validation outcome: assertion.dataHash.match
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.0, peak 26 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 3.58 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 32.99 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (88): synthetic likelihood 88/100; tells: hat merges with head with no visible ears or straps; fold-like ear shapes sit ambiguously under brim, overly smooth, idealized fur rendering with painterly micro-texture on face, whiskers unusually long, dense and uniformly bright, some originating from implausible positions, near-identical glossy eye reflections with slightly irregular pupil shapes
- **OpenAI Vision** (84): synthetic likelihood 84/100; tells: Chest fur forms unusually broad, layered, feather-like clumps, Cheek fur has a densely etched, repetitive texture, Ear contours merge ambiguously with fur beneath the hat brim, Highly polished eye and nose surfaces contrast with exaggerated fur detail
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: overly uniform airbrushed fur rendering, implausible ear integration under hat, perfect studio lighting and stylized depth of field blur

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
