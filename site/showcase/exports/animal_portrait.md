# SDA Vision analysis

- **File:** animal-portrait.jpg
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 78/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** bdc5c19d4211d9c9f9f8dce5bf4e4dec29e9b32e308ff12a60979481e928154f
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:02+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 90 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 78 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 75 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 47 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Ear anatomy ambiguous: folded ears appear to merge into the hat brim and head without a clear boundary
  - Whiskers emerge from implausible origins (some from cheeks and neck, not only the muzzle pads) with inconsistent thickness and length
  - Fur texture uniformly hyper-detailed and 'painted' across the face, with an overly regular tabby pattern
  - Hat fits the cat's head perfectly with no deformation or visible support, typical of generated props
  - Idealized 'golden hour' bokeh and rim lighting consistent with stylized text-to-image output
- **OpenAI Vision**:
  - Chest fur forms unusually broad, sculpted clumps compared with the fine facial fur
  - Several whiskers have angular bends and uneven thickness
  - Highly regular facial detailing and unusually smooth, uniform iris textures
  - Hat brim and partly concealed ears have ambiguous contact geometry
  - Consistent warm rim lighting and plausible background blur provide some photographic cues
- **Gemini Vision**:
  - Implausible ear anatomy under hat brim
  - Hyper-smooth rendering of fur and felt texture
  - Unnatural symmetry in whisker and facial layout
  - Diffuse artificial lighting effects
  - Caveat: High-quality digital art or photo manipulation can occasionally mimic diffusion model artifacts.
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

- **Claude Vision** (90): synthetic likelihood 90/100; tells: ear anatomy ambiguous: folded ears appear to merge into the hat brim and head without a clear boundary, whiskers emerge from implausible origins (some from cheeks and neck, not only the muzzle pads) with inconsistent thickness and length, fur texture uniformly hyper-detailed and 'painted' across the face, with an overly regular tabby pattern, hat fits the cat's head perfectly with no deformation or visible support, typical of generated props
- **OpenAI Vision** (78): synthetic likelihood 78/100; tells: Chest fur forms unusually broad, sculpted clumps compared with the fine facial fur, Several whiskers have angular bends and uneven thickness, Highly regular facial detailing and unusually smooth, uniform iris textures, Hat brim and partly concealed ears have ambiguous contact geometry
- **Gemini Vision** (75): synthetic likelihood 75/100; tells: implausible ear anatomy under hat brim, hyper-smooth rendering of fur and felt texture, unnatural symmetry in whisker and facial layout, diffuse artificial lighting effects

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: File integrity: validated. Signer trust: unresolved under the current local policy. The recorded declarations remain available for review and are not used as a decisive provenance finding. Manifest declares AI-generated content.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
