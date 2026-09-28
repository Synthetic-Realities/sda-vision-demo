# SDA Vision analysis

- **File:** infographic.pdf
- **Tool version:** 0.1.0
- **Verdict:** inconclusive (confidence low)
- **Indicative score:** 27/100 (rounded mean of available frame scores; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** 02915f051b6eb2c9ef0c21f5bb20c4229ca21324bf20172f3867c32c299a5924
- **Headline:** Inconclusive
- **Input:** pdf - 4 frame(s) analysed of 15 found
- **Generated:** 2026-09-26T22:31:05+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> The sampled frames leave the assessment inconclusive. Review the frame results and source context.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## Cite this analysis

Software (Harvard): Martin, S. (2026) SDA Vision: Synthetic-media Discourse Analysis (version 0.1.0) [Computer software]. Manchester Metropolitan University. Available at: https://sdavision.io/
Software creator: Dr Sam Martin, Smart Data Research UK (UKRI) Fellow, Manchester Metropolitan University (MMU). ORCID: https://orcid.org/0000-0002-4466-8374.
Funding acknowledgement: This work was supported by Smart Data Research UK, a UKRI investment; Grant number UKRI4010.
Analysis record: File: infographic.pdf; media type: pdf; recorded at: 2026-09-26T22:31:05+00:00; models: claude-opus-5-5, gemini-3.8-flash, gpt-6-astra.

## How the file was read

- PDF preparation: pdf-input-2026-09-26.1 (pypdf text/figures; PDFium page rendering).
- Extracted 4 embedded figure(s) of 15 found (figure mode).
- No selectable text layer - vision models read the page/figure images.
- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Per-frame breakdown

| Frame | Verdict | Rating |
|---|---|---|
| figure p1 | inconclusive | 28 |
| figure p6 | inconclusive | 25 |
| figure p10 | inconclusive | 25 |
| figure p15 | inconclusive | 30 |

_Frames can disagree; review them individually rather than treating the document as one number._

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 62 | low | additional |
| OpenAI Vision | gpt-6-astra | vision | ok | inconclusive | 15 | low | additional |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 30 | medium | additional |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Frame figure p1: 40/100
  - Frame figure p6: 45/100
  - Frame figure p10: 45/100
  - Frame figure p15: 62/100
  - Not a camera photo: flat digital graphic/slide, so photographic forensics (sensor noise, lens blur, lighting) do not apply
- **OpenAI Vision**:
  - Frame figure p1: 12/100
  - Frame figure p6: 15/100
  - Frame figure p10: 12/100
  - Frame figure p15: 15/100
  - Legible, coherent text with consistent repeated letterforms.
- **Gemini Vision**:
  - Frame figure p1: 28/100
  - Frame figure p6: 25/100
  - Frame figure p10: 25/100
  - Frame figure p15: 30/100
  - Sharp vector-style geometric graphics
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - Frame figure p1: 41/100
  - Frame figure p6: 41/100
  - Frame figure p10: 41/100
  - Frame figure p15: 41/100
  - No camera EXIF (common in AI exports, screenshots, and re-saves).

## Evidence supporting this verdict

- (none)

## Additional findings

Shown separately from the combined assessment.

- **Claude Vision**: Worst of 4 frames (figure p15): synthetic likelihood 62/100; tells: not a camera photo: flat digital graphic/slide, so photographic forensics (sensor noise, lens blur, lighting) do not apply, inconsistent centering of body text lines, with ragged, uneven offsets unlike typical layout-software alignment, polygonal network line-art with segments that end in mid-air, fade unevenly, and break into stray dashed fragments on the left, faint mottled texture in the flat background, atypical of vector-exported slides
- **OpenAI Vision**: Worst of 4 frames (figure p6): synthetic likelihood 15/100; tells: Legible, coherent text with consistent repeated letterforms., Regular two-column layout with aligned rounded panels., Consistent bold labels and uniform bullet styling., No photographic base or identifiable inpainting boundaries.
- **Gemini Vision**: Worst of 4 frames (figure p15): synthetic likelihood 30/100; tells: sharp vector-style geometric graphics, clean digital typography, standard graphic design layout artifacts
- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Extracted text

```
Geographic Discourse Extremes | The Sceptics (USA & Italy) | • Primary Driver: Mistrust in institutions (CDC, FDA, Italy's ASL). | • Core Theme: Extrapolating harm from contraindicated vaccines to recommended ones. | • Vector Activity: High presence of bot-associated hashtags. | The Advocates (India & UK) | • Primary Driver: Proactive, visible public health campaigns. | • Core Theme: Child protection and successful programme launches (e.g., India's Mission Indradhanush). | • Vector Activity: Organic tagging of trusted bodies (Public Health England).
```

## How this assessment was reached

1. `frame_agreement` frames=4; synthetic_frames=0; authentic_frames=0; rating_spread=5
2. `verdict` value=inconclusive; confidence=low; reason=The sampled frames leave the assessment inconclusive. Review the frame results and source context.
