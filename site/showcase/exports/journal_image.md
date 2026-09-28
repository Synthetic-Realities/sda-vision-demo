# SDA Vision analysis

- **File:** journal-image.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 78/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** b11aa1e8c5c17a9496d362987bd4bf0c00a83bccd3a4a704f0f6ab7a7cf6fc8d
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:06+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software citation: Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: journal-image.png; media type: image; recorded at: 2026-09-26T22:31:06+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 90 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 78 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Uniform painterly-photoreal rendering style shared across the main scene and all six portrait tiles, typical of a single image-generation pass
  - Stock-archetype faces with exaggerated, near-identical 'distressed' expressions and similar desaturated grading
  - Over-smooth yet hyper-detailed skin texture (pores and stubble rendered evenly, slightly waxy highlights)
  - Syringe and gloved-hand geometry ambiguous: needle entry point and grip read loosely, with fingers merging around the barrel
  - Man's hand pinching the sleeve has soft, poorly separated knuckles
- **OpenAI Vision**:
  - Main vaccination scene and six inset portraits share unusually uniform cinematic lighting and textured skin rendering.
  - Syringe barrel, plunger, and gloved grip have indistinct, difficult-to-reconcile geometry.
  - Hair and facial creases in several portraits appear unusually densely sharpened against smooth backgrounds.
  - Crisp, coherent typography and neatly aligned panels indicate a designed graphic but do not independently establish AI use.
  - Caveat: A professionally designed collage of stock photographs could produce similar styling; source assets and provenance are needed to distinguish generated portraits from conventional editing.
- **Gemini Vision**:
  - Model read this as AI editing over a photographic base image
  - Hyper-rendered skin textures
  - Characteristic AI portrait lighting across multiple subjects
  - Slightly unnatural finger and needle interaction
  - Stereotyped expressive posing common in text-to-image models
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

- **Claude Vision** (90): synthetic likelihood 90/100; tells: uniform painterly-photoreal rendering style shared across the main scene and all six portrait tiles, typical of a single image-generation pass, stock-archetype faces with exaggerated, near-identical 'distressed' expressions and similar desaturated grading, over-smooth yet hyper-detailed skin texture (pores and stubble rendered evenly, slightly waxy highlights), syringe and gloved-hand geometry ambiguous: needle entry point and grip read loosely, with fingers merging around the barrel
- **OpenAI Vision** (78): synthetic likelihood 78/100; tells: Main vaccination scene and six inset portraits share unusually uniform cinematic lighting and textured skin rendering., Syringe barrel, plunger, and gloved grip have indistinct, difficult-to-reconcile geometry., Hair and facial creases in several portraits appear unusually densely sharpened against smooth backgrounds., Crisp, coherent typography and neatly aligned panels indicate a designed graphic but do not independently establish AI use.
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: model read this as AI editing over a photographic base image, hyper-rendered skin textures, characteristic AI portrait lighting across multiple subjects, slightly unnatural finger and needle interaction

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
Research Brief • 2025
Neurological Reports Following
Immunisation: A Preliminary Review
NEW REVIEW RAISES QUESTIONS
ABOUT mRNA SHOTS
Z
Z
MOOD
MEMORY
SLEEP
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
