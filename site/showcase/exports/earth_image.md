# SDA Vision analysis

- **File:** earth-image.jpg
- **Tool version:** 0.1.0
- **Verdict:** authentic likely (confidence medium)
- **Indicative score:** 5/100 (median of available model ratings; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** a4bad2aba040fd992aff7483eee6166943e232061b82d7149b2060786719753b
- **Headline:** Leaning authentic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T17:54:47+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Recomputed locally from the same saved provider replies acquired under run five-examples-20260926-r1. No new provider requests. Original report 6201ac7a-3540-405f-b234-0346b77f7672 was generated at 2026-09-26T17:38:41+00:00 under method publication-repair-2026-09-24.3; that report is preserved.
- Method verdict-consistency-2026-09-26.1: directional model votes require matching explicit verdicts and rating thresholds. Inconclusive replies retain their ratings and remain undecided observations.
- Presentation copy of saved report cf784e2f-0554-4bed-8880-c825ae7b8282. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | authentic likely | 5 | high | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | authentic likely | 2 | high | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 15 | high | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 47 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Composition matches the widely circulated 1972 Apollo 17 'Blue Marble' photograph (AS17-148-22727)
  - Geographically accurate Africa, Arabian Peninsula, Red Sea, Gulf of Aden and Madagascar outlines
  - Antarctic ice cap consistent with December solstice illumination
  - Physically coherent cloud structures: cyclonic swirls, frontal bands, open-cell cumulus fields
  - Film-scan grain and slight color cast consistent with analog Hasselblad film digitization
- **OpenAI Vision**:
  - Coherent coastlines of Africa, Madagascar and the Arabian Peninsula
  - Irregular, finely detailed cloud systems with consistent spherical foreshortening
  - Natural atmospheric haze and gradual shading around Earth's limb
  - Fine photographic grain and slight color fringing along the globe edge
  - Caveat: Resembles the historical Blue Marble photograph; source-file comparison is needed to establish provenance and exclude subtle edits.
- **Gemini Vision**:
  - Authentic Apollo 17 'Blue Marble' photograph
  - Natural film grain structure
  - Consistent atmospheric limb glow
  - Accurate meteorological cloud swirls
  - Caveat: High-profile historic images are frequently duplicated, cropped, or color-adjusted across digital archives.
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 0.5, peak 10 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 4.61 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 25.63 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (5): synthetic likelihood 5/100; tells: composition matches the widely circulated 1972 Apollo 17 'Blue Marble' photograph (AS17-148-22727), geographically accurate Africa, Arabian Peninsula, Red Sea, Gulf of Aden and Madagascar outlines, Antarctic ice cap consistent with December solstice illumination, physically coherent cloud structures: cyclonic swirls, frontal bands, open-cell cumulus fields
- **OpenAI Vision** (2): synthetic likelihood 2/100; tells: Coherent coastlines of Africa, Madagascar and the Arabian Peninsula, Irregular, finely detailed cloud systems with consistent spherical foreshortening, Natural atmospheric haze and gradual shading around Earth's limb, Fine photographic grain and slight color fringing along the globe edge
- **Gemini Vision** (15): synthetic likelihood 15/100; tells: authentic Apollo 17 'Blue Marble' photograph, natural film grain structure, consistent atmospheric limb glow, accurate meteorological cloud swirls

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=[]; authentic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=authentic_likely; confidence=medium; reason=3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.
