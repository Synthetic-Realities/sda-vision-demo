# SDA Vision analysis

- **File:** journal-diagram.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence medium)
- **Indicative score:** 68/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** c9a680547869618d7c63648d317b1f27c03ede59d5113a7cd6818f5ce2bd654e
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:05+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 2 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software (Harvard): Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: journal-diagram.png; media type: image; recorded at: 2026-09-26T22:31:05+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 80 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | inconclusive | 45 | low | additional |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 68 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Uniform soft airbrushed painterly shading across all elements, typical of current image-generation models
  - Whole composite (portrait, anatomy, inset, icons, typography) rendered in one seamless style rather than assembled from separate assets
  - Anatomically loose vasculature: arteries drawn over the brain surface and an idealized carotid path from neck to cortex
  - Generic glowing highlights (red cortical hotspot, yellow injection-site glow) used as stylized emphasis
  - Repetitive near-identical lipid-nanoparticle and red blood cell motifs with slight random variation
- **OpenAI Vision**:
  - Entire image is a medical illustration, with no camera-photo base visible.
  - Headings and labels are legible, with consistent serif typography and aligned layout.
  - Anatomy and cellular elements use smooth shaded fills and clean outlines compatible with conventional digital illustration.
  - Repeated particle motifs have variable internal squiggles, but no decisive generation artifact is visible.
  - Caveat: Conventional digital artwork and AI-assisted illustration can look alike; source files and provenance are needed to distinguish them.
- **Gemini Vision**:
  - Model read this as AI editing over a photographic base image
  - Sterile digital rendering style
  - Slightly inconsistent anatomical blending in syringe and hand
  - Typical AI-generated vector/digital medical illustration texture
  - Clean modern typography composited over generated artwork
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.8, peak 62 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 11.38 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 19.81 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (80): synthetic likelihood 80/100; tells: uniform soft airbrushed painterly shading across all elements, typical of current image-generation models, whole composite (portrait, anatomy, inset, icons, typography) rendered in one seamless style rather than assembled from separate assets, anatomically loose vasculature: arteries drawn over the brain surface and an idealized carotid path from neck to cortex, generic glowing highlights (red cortical hotspot, yellow injection-site glow) used as stylized emphasis
- **Gemini Vision** (68): synthetic likelihood 68/100; tells: model read this as AI editing over a photographic base image, sterile digital rendering style, slightly inconsistent anatomical blending in syringe and hand, typical AI-generated vector/digital medical illustration texture

## Additional findings

Shown separately from the combined assessment.

- **OpenAI Vision**: synthetic likelihood 45/100; tells: Entire image is a medical illustration, with no camera-photo base visible., Headings and labels are legible, with consistent serif typography and aligned layout., Anatomy and cellular elements use smooth shaded fills and clean outlines compatible with conventional digital illustration., Repeated particle motifs have variable internal squiggles, but no decisive generation artifact is visible.
- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
Biomedical Signals • Research Commentary • 2025 | mRNA Vaccination and the Brain: A Proposed Pathway | CAN PARTICLES CROSS THE BLOOD–BRAIN BARRIER? | Brain | Bloodstream | Suggested outcomes | Inflammation | Brain fog | Memory changes | Figure 1. Hypothetical pathway illustrated for discussion.
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'Gemini Vision']; authentic=[]; uncertain=['OpenAI Vision']; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=medium; reason=2 models agree this is likely synthetic.
