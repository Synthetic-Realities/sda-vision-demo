# SDA Vision analysis

- **File:** infographic.pdf
- **Tool version:** 0.1.0
- **Verdict:** inconclusive (confidence low)
- **Indicative score:** 26/100 (rounded mean of available frame scores; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** 02915f051b6eb2c9ef0c21f5bb20c4229ca21324bf20172f3867c32c299a5924
- **Headline:** Inconclusive
- **Input:** pdf - 4 frame(s) analysed of 15 found
- **Generated:** 2026-09-26T17:54:48+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> The sampled frames leave the assessment inconclusive. Review the frame results and source context.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Extracted 4 embedded figure(s) of 15 found (figure mode).
- No selectable text layer - vision models read the page/figure images.
- Recomputed locally from the same saved provider replies acquired under run five-examples-20260926-r1. No new provider requests. Original report 67783866-5136-47c8-95ce-ff7e7f37c6d3 was generated at 2026-09-26T17:38:42+00:00 under method publication-repair-2026-09-24.3; that report is preserved.
- Method verdict-consistency-2026-09-26.1: directional model votes require matching explicit verdicts and rating thresholds. Inconclusive replies retain their ratings and remain undecided observations.
- Presentation copy of saved report aac43583-5a80-4042-988f-028d0b7bfae8. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Per-frame breakdown

| Frame | Verdict | Rating |
|---|---|---|
| figure p1 | authentic likely | 25 |
| figure p6 | inconclusive | 25 |
| figure p10 | authentic likely | 25 |
| figure p15 | inconclusive | 28 |

_Frames can disagree; review them individually rather than treating the document as one number._

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | inconclusive | 55 | low | additional |
| OpenAI Vision | gpt-6-astra | vision | ok | inconclusive | 15 | low | additional |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 28 | medium | additional |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Frame figure p1: 45/100
  - Frame figure p6: 40/100
  - Frame figure p10: 35/100
  - Frame figure p15: 55/100
  - No camera-photo content; digitally rendered slide graphic, so photographic forensics (grain, lens blur, lighting) do not apply
- **OpenAI Vision**:
  - Frame figure p1: 8/100
  - Frame figure p6: 15/100
  - Frame figure p10: 5/100
  - Frame figure p15: 15/100
  - Consistent, legible typography throughout both columns
- **Gemini Vision**:
  - Frame figure p1: 25/100
  - Frame figure p6: 25/100
  - Frame figure p10: 25/100
  - Frame figure p15: 28/100
  - Clean vector typography
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

- **Claude Vision**: Worst of 4 frames (figure p15): synthetic likelihood 55/100; tells: no camera-photo content; digitally rendered slide graphic, so photographic forensics (grain, lens blur, lighting) do not apply, irregular, non-geometric low-poly line networks with inconsistent node joins and fading, typical of AI image-generator decorative motifs, red-to-green left/right mirrored decoration with loosely matched structure, heavy bold text with slightly soft drop-shadow/halo edges on headline
- **OpenAI Vision**: Worst of 4 frames (figure p6): synthetic likelihood 15/100; tells: Consistent, legible typography throughout both columns, Regular rounded panels and aligned borders characteristic of conventional slide design, No obvious malformed lettering or incoherent graphic elements, Entire image is a text infographic, with no photographic detail to assess
- **Gemini Vision**: Worst of 4 frames (figure p15): synthetic likelihood 28/100; tells: clean vector typography, standard geometric graphic design elements, absence of diffusion generation artifacts
- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Extracted text

```
Geographic Discourse Extremes | The Sceptics (USA & Italy) | • Primary Driver: Mistrust in institutions (CDC, FDA, Italy's ASL). | • Core Theme: Extrapolating harm from contraindicated vaccines to recommended ones. | • Vector Activity: High presence of bot-associated hashtags. | The Advocates (India & UK) | • Primary Driver: Proactive, visible public health campaigns. | • Core Theme: Child protection and successful programme launches (e.g., India's Mission Indradhanush). | • Vector Activity: Organic tagging of trusted bodies (Public Health England).
```

## How this assessment was reached

1. `frame_agreement` frames=4; synthetic_frames=0; authentic_frames=2; rating_spread=3
2. `verdict` value=inconclusive; confidence=low; reason=The sampled frames leave the assessment inconclusive. Review the frame results and source context.
