# SDA Vision analysis

- **File:** animated-video.mov
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence medium)
- **Indicative score:** 84/100 (rounded mean of available frame scores; not a calibrated probability)
- **Method version:** pdf-preparation-2026-09-26.1
- **Input SHA-256:** af5b2c84950d66ce32b4d7f603314a7fc70a9353d397ca71aa78d35e2327ce23
- **Headline:** Leaning synthetic
- **Input:** video - 4 frame(s) analysed
- **Generated:** 2026-09-27T21:00:50.708133+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 4 of 4 frames read as synthetic or edited.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Duration 15s; sampled 4 frame(s).
- Audio tracks inspected locally. Soundtrack uploads require a separate optional check; AI-origin detection from sound is outside this workflow.
- Visual assessment covers the sampled still frames. Soundtrack checks are recorded separately; continuous motion is outside this assessment.
- Completed provider replies recovered offline after a local thumbnail error. Response-to-frame associations were reconstructed from the distinct scene descriptions; individual API timings were not retained.

## Local soundtrack inspection

- Audio inspection: present; tracks: 1.
- Track 0: aac, 2 channel(s), 44100 Hz; duration 15.070499s; decode decoded; 3/3 sampled windows above -60 dBFS after mono downmix.
- Sample windows: 0.0s + 3.0s; 6.035s + 3.0s; 12.07s + 3.0s
- Original-file credentials are recorded separately. Credential coverage of this audio track: unresolved.
- Audio-level measurements cover the sampled windows. The remaining audio has not been inspected by this check.

## Assessment coverage

- Visual verdicts for videos cover the sampled still frames. Standalone-audio content assessments cover the transcript. Soundtrack-origin detection and continuous-motion analysis are outside these assessments.
- Original-file credentials, excerpt descriptions and visual interpretation are recorded separately. Credential coverage of an individual audio track remains unresolved by this workflow.

## Per-frame breakdown

| Frame | Verdict | Rating |
|---|---|---|
| 00:03 | synthetic likely | 85 |
| 00:06 | synthetic likely | 83 |
| 00:09 | synthetic likely | 80 |
| 00:12 | synthetic likely | 88 |

_Frames can disagree; review them individually rather than treating the document as one number._

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 90 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 88 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 68 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 47 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Frame 00:03: 85/100
  - Frame 00:06: 88/100
  - Frame 00:09: 90/100
  - Frame 00:12: 88/100
  - Glowing swirling portal inside brick archway rendered seamlessly into scene lighting
- **OpenAI Vision**:
  - Frame 00:03: 85/100
  - Frame 00:06: 83/100
  - Frame 00:09: 80/100
  - Frame 00:12: 88/100
  - Translucent figures overlap the storefront with smeared, poorly resolved anatomy.
- **Gemini Vision**:
  - Frame 00:03: 68/100
  - Frame 00:06: 68/100
  - Frame 00:09: 38/100
  - Frame 00:12: 35/100
  - CGI or generative rendering textures on creature scales
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - Frame 00:03: 47/100
  - Frame 00:06: 47/100
  - Frame 00:09: 47/100
  - Frame 00:12: 47/100
  - No camera EXIF (common in AI exports, screenshots, and re-saves).

## Evidence supporting this verdict

- **Claude Vision** (90): Worst of 4 frames (00:09): synthetic likelihood 90/100; tells: glowing swirling portal inside brick archway rendered seamlessly into scene lighting, smooth, waxy skin texture with painterly softness on all three faces, uniformly cinematic teal-orange grade and volumetric haze typical of generative video models, fruit in crates and baskets rendered as repetitive, near-identical blobs with little individual detail
- **OpenAI Vision** (88): Worst of 4 frames (00:12): synthetic likelihood 88/100; tells: Translucent figures overlap the storefront with smeared, poorly resolved anatomy., Window figures do not clearly correspond to the foreground woman's pose or position., Dragon-like creature behind the left figure has soft, indistinct anatomical boundaries., Costume details and produce have unusually uniform, painterly surface smoothing.
- **Gemini Vision** (68): Worst of 4 frames (00:03): synthetic likelihood 68/100; tells: CGI or generative rendering textures on creature scales, unnatural lighting blend between creature and tunnel background, diffuse glow inconsistency around wrist gauntlet projection, smooth plastic-like skin texture on subject

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
SLANE NW EASE (partially legible, likely garbled)
```

## How this assessment was reached

1. `frame_agreement` frames=4; synthetic_frames=4; authentic_frames=0; rating_spread=8
2. `verdict` value=synthetic_likely; confidence=medium; reason=4 of 4 frames read as synthetic or edited.
