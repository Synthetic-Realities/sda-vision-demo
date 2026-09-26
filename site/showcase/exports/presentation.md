# SDA Vision analysis

- **File:** presentation.pptx
- **Tool version:** 0.1.0
- **Verdict:** inconclusive (confidence low)
- **Indicative score:** 26/100 (rounded mean of available frame scores; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** d0ec89da564078611922195fca82364f2f8e63d253d02a6d9bb672a8265c5f15
- **Headline:** Inconclusive
- **Input:** pptx - 4 frame(s) analysed of 14 found
- **Generated:** 2026-09-26T17:54:46+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> The sampled frames leave the assessment inconclusive. Review the frame results and source context.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- 14 slides; sampled 4 of 14 embedded slide image(s).
- Recomputed locally from the same saved provider replies acquired under run five-examples-20260926-r1. No new provider requests. Original report f08956d6-23e1-4043-972d-6af6e3cd2603 was generated at 2026-09-26T17:38:39+00:00 under method publication-repair-2026-09-24.3; that report is preserved.
- Method verdict-consistency-2026-09-26.1: directional model votes require matching explicit verdicts and rating thresholds. Inconclusive replies retain their ratings and remain undecided observations.
- Presentation copy of saved report d5854304-5dab-4b76-945b-d844e5fe7c44. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Per-frame breakdown

| Frame | Verdict | Rating |
|---|---|---|
| slide 1 | inconclusive | 25 |
| slide 5 | inconclusive | 28 |
| slide 10 | authentic likely | 25 |
| slide 14 | inconclusive | 25 |

_Frames can disagree; review them individually rather than treating the document as one number._

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | inconclusive | 58 | low | additional |
| OpenAI Vision | gpt-6-astra | vision | ok | inconclusive | 15 | medium | additional |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 28 | medium | additional |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Frame slide 1: 58/100
  - Frame slide 5: 58/100
  - Frame slide 10: 55/100
  - Frame slide 14: 55/100
  - Network diagram geometry is approximately but not mathematically regular: uneven node spacing and edge endpoints that do not always terminate cleanly on nodes
- **OpenAI Vision**:
  - Frame slide 1: 15/100
  - Frame slide 5: 15/100
  - Frame slide 10: 12/100
  - Frame slide 14: 10/100
  - Presentation-slide layout rather than a camera photograph
- **Gemini Vision**:
  - Frame slide 1: 25/100
  - Frame slide 5: 28/100
  - Frame slide 10: 25/100
  - Frame slide 14: 25/100
  - Sharp vector-style typography
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - Frame slide 1: 41/100
  - Frame slide 5: 41/100
  - Frame slide 10: 41/100
  - Frame slide 14: 41/100
  - No camera EXIF (common in AI exports, screenshots, and re-saves).

## Evidence supporting this verdict

- (none)

## Additional findings

Shown separately from the combined assessment.

- **Claude Vision**: Worst of 4 frames (slide 1): synthetic likelihood 58/100; tells: network diagram geometry is approximately but not mathematically regular: uneven node spacing and edge endpoints that do not always terminate cleanly on nodes, some edges appear semi-transparent or softly blurred in an inconsistent way, unlike typical crisp vector rendering, teal-to-orange colour transition across nodes is painterly rather than rule-based, faint background polygon mesh with irregular, fading line segments
- **OpenAI Vision**: Worst of 4 frames (slide 1): synthetic likelihood 15/100; tells: Presentation-slide layout rather than a camera photograph, Legible typography with consistent letterforms and alignment, Network illustration uses clean straight edges and regularly placed circular nodes, No obvious generative distortions; conventional vector graphics could explain the design
- **Gemini Vision**: Worst of 4 frames (slide 5): synthetic likelihood 28/100; tells: sharp vector-style typography, clean standard digital design elements, absence of generative diffusion artifacts, structured geometric layout
- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Extracted text

```
Catalyst 2: The Conspiracy Ecosystem | 1 | #Plandemic | The Threat Hoax | Minimising the virus itself. “It’s just the flu,” preferring natural immunity over interventions. | #Scamdemic | 2 | #COVID1984 | The Control Mechanism | Belief that mandates test public compliance, equating health rules to authoritarian mouth-gags. | #MaskTyranny | 3 | The Micro-Constituent Fear | Targeting vaccines specifically: fears of mRNA DNA-alteration, microchips, infertility, and Bill Gates narratives. | Once a citizen accepted the ‘Control Mechanism’ premise for masks, transitioning to the ‘Micro-Constituent Fear’ for vaccines required almost no psychological leap.
```

## How this assessment was reached

1. `frame_agreement` frames=4; synthetic_frames=0; authentic_frames=1; rating_spread=3
2. `verdict` value=inconclusive; confidence=low; reason=The sampled frames leave the assessment inconclusive. Review the frame results and source context.
