# SDA Vision analysis

- **File:** earth-image.jpg
- **Tool version:** 0.1.0
- **Verdict:** authentic likely (confidence medium)
- **Indicative score:** 4/100 (median of available model ratings; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** a4bad2aba040fd992aff7483eee6166943e232061b82d7149b2060786719753b
- **Headline:** Leaning authentic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T22:31:03+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software (Harvard): Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: earth-image.jpg; media type: image; recorded at: 2026-09-26T22:31:03+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | authentic likely | 4 | high | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | authentic likely | 2 | high | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 25 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 47 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Visually consistent with the widely documented Apollo 17 'Blue Marble' photograph (NASA AS17-148-22727, Dec 1972)
  - Geographically accurate coastlines: Africa, Arabian Peninsula, Red Sea, Gulf of Aden, Madagascar, Antarctic ice cap
  - Physically coherent cloud systems and cyclonic swirls with plausible meteorological structure
  - Film-scan grain and slight color cast consistent with analog photography
  - Natural limb shading and terminator-free full-disc illumination consistent with sun behind the camera
- **OpenAI Vision**:
  - Coherent African, Arabian Peninsula, and Madagascar coastlines
  - Intricate, nonrepeating cloud bands and storm spirals
  - Consistent atmospheric haze and foreshortening toward Earth's limb
  - Fine grain and slight softness consistent with a scanned photograph
  - Composition closely resembles the historical Blue Marble photograph
- **Gemini Vision**:
  - Authentic film grain
  - Consistent atmospheric limb scatter
  - Historically documented cloud formations
  - Natural optical sensor characteristics
  - Caveat: High-profile historical images can be digitally remastered or simulated by generative models.
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

- **Claude Vision** (4): synthetic likelihood 4/100; tells: visually consistent with the widely documented Apollo 17 'Blue Marble' photograph (NASA AS17-148-22727, Dec 1972), geographically accurate coastlines: Africa, Arabian Peninsula, Red Sea, Gulf of Aden, Madagascar, Antarctic ice cap, physically coherent cloud systems and cyclonic swirls with plausible meteorological structure, film-scan grain and slight color cast consistent with analog photography
- **OpenAI Vision** (2): synthetic likelihood 2/100; tells: Coherent African, Arabian Peninsula, and Madagascar coastlines, Intricate, nonrepeating cloud bands and storm spirals, Consistent atmospheric haze and foreshortening toward Earth's limb, Fine grain and slight softness consistent with a scanned photograph
- **Gemini Vision** (25): synthetic likelihood 25/100; tells: authentic film grain, consistent atmospheric limb scatter, historically documented cloud formations, natural optical sensor characteristics

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=[]; authentic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=authentic_likely; confidence=medium; reason=3 models lean authentic with matching verdicts and ratings. Review the other findings, original source and context alongside this result.
