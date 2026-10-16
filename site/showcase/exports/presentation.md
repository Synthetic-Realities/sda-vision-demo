# SDA Vision analysis

- **File:** presentation.pptx
- **Tool version:** 0.1.0
- **Verdict:** inconclusive (confidence low)
- **Indicative score:** 27/100 (rounded mean of available frame scores; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** d0ec89da564078611922195fca82364f2f8e63d253d02a6d9bb672a8265c5f15
- **Headline:** Inconclusive
- **Input:** pptx - 4 frame(s) analysed of 14 found
- **Generated:** 2026-09-26T22:31:28+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> The sampled frames leave the assessment inconclusive. Review the frame results and source context.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- 14 slides; sampled 4 of 14 embedded slide image(s).
- Fresh provider replies acquired for eleven-examples-refresh-20260926-r1; report assembled locally from the saved responses without further API calls.
- Provider latency values are restored from the acquisition receipts (maximum sampled-frame latency per provider); raw replies and assessment results are unchanged by this bookkeeping step.

## Per-frame breakdown

| Frame | Verdict | Rating |
|---|---|---|
| slide 1 | inconclusive | 28 |
| slide 5 | inconclusive | 28 |
| slide 10 | inconclusive | 25 |
| slide 14 | inconclusive | 28 |

_Frames can disagree; review them individually rather than treating the document as one number._

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 60 | low | additional |
| OpenAI Vision | gpt-6-astra | vision | ok | inconclusive | 20 | low | additional |
| Gemini Vision | gemini-3.8-flash | vision | ok | authentic likely | 28 | medium | additional |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Frame slide 1: 60/100
  - Frame slide 5: 55/100
  - Frame slide 10: 58/100
  - Frame slide 14: 40/100
  - Network diagram is decorative and roughly symmetric rather than a data-driven force-directed layout
- **OpenAI Vision**:
  - Frame slide 1: 15/100
  - Frame slide 5: 20/100
  - Frame slide 10: 15/100
  - Frame slide 14: 15/100
  - Consistently legible text with coherent letterforms and regular spacing
- **Gemini Vision**:
  - Frame slide 1: 28/100
  - Frame slide 5: 28/100
  - Frame slide 10: 25/100
  - Frame slide 14: 28/100
  - Clean vector geometry
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

- **Claude Vision**: Worst of 4 frames (slide 1): synthetic likelihood 60/100; tells: network diagram is decorative and roughly symmetric rather than a data-driven force-directed layout, inconsistent node sizes and some edges ending without clear nodes, semi-transparent, softly blurred overlapping edge layers with painterly anti-aliasing, smooth teal-to-orange color gradient across the graph unrelated to any legend
- **OpenAI Vision**: Worst of 4 frames (slide 5): synthetic likelihood 20/100; tells: Consistently legible text with coherent letterforms and regular spacing, Four circular nodes with uniform glow effects and thin connecting lines, Aligned text blocks and repeated geometric network decorations typical of presentation graphics, No photographic subjects or camera texture available for assessment
- **Gemini Vision**: Worst of 4 frames (slide 1): synthetic likelihood 28/100; tells: clean vector geometry, standard digital typography, consistent presentation graphic layout, absence of generative diffusion artifacts
- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Extracted text

```
Catalyst 2: The Conspiracy Ecosystem | 1 The Threat Hoax: Minimising the virus itself. “It’s just the flu,” preferring natural immunity over interventions. | #Plandemic | #Scamdemic | 2 The Control Mechanism: Belief that mandates test public compliance, equating health rules to authoritarian mouth-gags. | #COVID1984 | #MaskTyranny | 3 The Micro-Constituent Fear: Targeting vaccines specifically: fears of mRNA DNA-alteration, microchips, infertility, and Bill Gates narratives. | Once a citizen accepted the ‘Control Mechanism’ premise for masks, transitioning to the ‘Micro-Constituent Fear’ for vaccines required almost no psychological leap.
```

## How this assessment was reached

1. `frame_agreement` frames=4; synthetic_frames=0; authentic_frames=0; rating_spread=3
2. `verdict` value=inconclusive; confidence=low; reason=The sampled frames leave the assessment inconclusive. Review the frame results and source context.
