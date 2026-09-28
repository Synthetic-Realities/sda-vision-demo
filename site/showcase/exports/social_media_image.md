# SDA Vision analysis

- **File:** social-media-image.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 93/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** f849e223762889e4d091fdf09caae3de19bff4cdc6e0024b50379276318f9fe7
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:29+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software citation: Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: social-media-image.png; media type: image; recorded at: 2026-09-26T22:31:29+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 93 | high | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 94 | high | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 82 | high | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Hyper-saturated cinematic orange/teal grading typical of image generators
  - Over-sharpened, uniformly detailed rabbit fur and whiskers with glowing rim light
  - Implausible scale and composition: intact rabbit resting directly on a mass of glossy visceral tissue
  - Organ mass has generic, anatomically incoherent structure with plastic-like specular highlights
  - Stylised glowing drop at needle tip and spark/glow effects without physical light source
- **OpenAI Vision**:
  - Syringe has unusually elaborate stacked connector rings and inconsistent graduation marks.
  - Foreground organs and vessels merge into convoluted, highly glossy forms without clear anatomical boundaries.
  - Rabbit fur and whiskers have unusually uniform sharpness and strong orange rim lighting.
  - Liquid, tissue, and syringe share exaggerated jewel-like highlights.
  - Small four-point sparkle emblem appears at the lower right.
- **Gemini Vision**:
  - Hyper-rendered specular textures on viscera
  - Unnatural fusion of biological anatomical forms
  - Stylized digital lighting and bokeh inconsistencies
  - AI-typical crisp fur detailing with odd spatial occlusion
  - Caveat: High-end 3D CGI or professional digital compositing can mimic generative-AI artifacts.
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 2.3, peak 74 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 7.53 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 22.81 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (93): synthetic likelihood 93/100; tells: hyper-saturated cinematic orange/teal grading typical of image generators, over-sharpened, uniformly detailed rabbit fur and whiskers with glowing rim light, implausible scale and composition: intact rabbit resting directly on a mass of glossy visceral tissue, organ mass has generic, anatomically incoherent structure with plastic-like specular highlights
- **OpenAI Vision** (94): synthetic likelihood 94/100; tells: Syringe has unusually elaborate stacked connector rings and inconsistent graduation marks., Foreground organs and vessels merge into convoluted, highly glossy forms without clear anatomical boundaries., Rabbit fur and whiskers have unusually uniform sharpness and strong orange rim lighting., Liquid, tissue, and syringe share exaggerated jewel-like highlights.
- **Gemini Vision** (82): synthetic likelihood 82/100; tells: hyper-rendered specular textures on viscera, unnatural fusion of biological anatomical forms, stylized digital lighting and bokeh inconsistencies, AI-typical crisp fur detailing with odd spatial occlusion

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
SHOCKING STUDY!
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
