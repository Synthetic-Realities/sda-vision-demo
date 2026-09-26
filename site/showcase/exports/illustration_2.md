# SDA Vision analysis

- **File:** illustration-2.png
- **Tool version:** 0.1.0
- **Verdict:** synthetic likely (confidence high)
- **Indicative score:** 85/100 (median of available model ratings; not a calibrated probability)
- **Method version:** verdict-consistency-2026-09-26.1
- **Input SHA-256:** 6693be931db5fb33a8cacfae382bf3bc79fc23b0d9f8e967015a663688d8c8f5
- **Headline:** Leaning synthetic
- **Input:** image - 1 frame(s) analysed
- **Generated:** 2026-09-26T17:54:46+00:00
- **Models:** claude-opus-5-5, gemini-3.8-flash, gpt-6-astra

> 3 models agree this is likely synthetic.

**Research assessment. Review alongside source information and context. When credentials are missing, origin remains unresolved by this check. Use these findings to inform a documented human review.**

## How the file was read

- Recomputed locally from the same saved provider replies acquired under run five-examples-20260926-r1. No new provider requests. Original report 6ea1656c-14d6-4257-bf8c-ed1a698f7865 was generated at 2026-09-26T17:38:40+00:00 under method publication-repair-2026-09-24.3; that report is preserved.
- Method verdict-consistency-2026-09-26.1: directional model votes require matching explicit verdicts and rating thresholds. Inconclusive replies retain their ratings and remain undecided observations.
- Presentation copy of saved report bced0e9e-ff82-4c4a-82bc-404c08a9a212. The descriptive filename replaces the earlier example ID for navigation. Original analysis dates, provider replies, scores and acquisition context are retained; no new model analysis.

## Provider ratings

| Provider | Model | Type | Status | Verdict | Rating | Confidence | Signal |
|---|---|---|---|---|---|---|---|
| Claude Vision | claude-opus-5-5 | vision | ok | synthetic likely | 88 | medium | supporting |
| OpenAI Vision | gpt-6-astra | vision | ok | synthetic likely | 85 | medium | supporting |
| Gemini Vision | gemini-3.8-flash | vision | ok | synthetic likely | 72 | medium | supporting |
| C2PA Content Credentials | - | provenance | ok | inconclusive |  | - | additional |
| Local forensic cues | - | forensic | ok | partially synthetic | 41 | low | additional |

## Key evidence per provider

- **Claude Vision**:
  - Garbled secondary text on props: 'ULTRA-PATCAI' on raised bottle, 'REMEDV' on jar, 'Buu' on picket sign
  - Picket sign text is repetitive and semantically incoherent ('Chloe Dubois Buy Chloe')
  - Poster is held by two people's hands yet also rests on an easel, which is physically redundant
  - Homogeneous glossy digital-comic rendering with uniform line weight and soft airbrushed shading typical of diffusion image models
  - Large crowd of stylistically similar, idealized faces with consistent generic features
- **OpenAI Vision**:
  - Bottle-gripping fingers have crowded, irregular contours and ambiguous joins to wrists.
  - The small placard repeats the name in the awkward sequence 'Chloe Dubois Buu Chloe'.
  - Uniform glossy facial shading and densely repeated hair contours across the illustrated crowd.
  - Some hands and arms overlap props with unclear anatomical connections.
  - Caveat: This is a digital illustration; stylization and manual compositing can mimic generation artifacts, so AI origin requires provenance review.
- **Gemini Vision**:
  - Stylized digital comic illustration style
  - Characteristic generative AI linework consistency
  - Overly smooth shading on faces and hair
  - Inconsistencies in minor background details
  - Caveat: Standard digital illustration techniques can closely mimic AI-generated comic and vector aesthetics.
- **C2PA Content Credentials**:
  - Embedded credentials: none found. Origin remains unresolved by this check.
  - Coverage: credentials embedded in the submitted file. External credentials were not retrieved.
  - Verifier: c2pa-python 0.37.12; native SDK 0.91.0; specification target 2.4; policy embedded-offline-reviewed-trust-v3.
  - Offline embedded-manifest verification; no network trust-list, manifest or revocation refresh.
  - No reviewed local C2PA trust snapshot installed. Provenance overrides are disabled.
- **Local forensic cues**:
  - No camera EXIF (common in AI exports, screenshots, and re-saves).
  - ELA mean 1.4, peak 24 (uniform high ELA can indicate generation/heavy edit).
  - High-frequency noise std 14.26 (very low/very uniform noise is a synthesis cue).
  - Spectral peakiness 13.87 (periodic frequency peaks can mark generated textures).

## Evidence supporting this verdict

- **Claude Vision** (88): synthetic likelihood 88/100; tells: garbled secondary text on props: 'ULTRA-PATCAI' on raised bottle, 'REMEDV' on jar, 'Buu' on picket sign, picket sign text is repetitive and semantically incoherent ('Chloe Dubois Buy Chloe'), poster is held by two people's hands yet also rests on an easel, which is physically redundant, homogeneous glossy digital-comic rendering with uniform line weight and soft airbrushed shading typical of diffusion image models
- **OpenAI Vision** (85): synthetic likelihood 85/100; tells: Bottle-gripping fingers have crowded, irregular contours and ambiguous joins to wrists., The small placard repeats the name in the awkward sequence 'Chloe Dubois Buu Chloe'., Uniform glossy facial shading and densely repeated hair contours across the illustrated crowd., Some hands and arms overlap props with unclear anatomical connections.
- **Gemini Vision** (72): synthetic likelihood 72/100; tells: stylized digital comic illustration style, characteristic generative AI linework consistency, overly smooth shading on faces and hair, inconsistencies in minor background details

## Additional findings

Shown separately from the combined assessment.

- **Local forensic cues**: Supporting observation; considered alongside the model assessments.
- **C2PA Content Credentials**: Embedded credentials: none found. Origin remains unresolved by this check.

## Visible text

```
Chloe Dubois is suffering “side effects”! Our unique detox patches are the ONLY answer! Buy them now! The true cure! | STOP YOUR DANGEROUS LIES! Chloe is healthy and pro-vaccine! Vaccines are proven safe! | The only “injury” is your grift! Our public health is not for sale. Science Defends All! | HOSPITAL | EMERGENCY | Chloe Dubois Buu Chloe | ULTRA-PATCAI | ULTRA-PATCH | CHLOE-CLEANSE | REMEDV | VACCINE FACTS | CHLOE DUBOIS | SDA
```

## How this assessment was reached

1. `override` outcome=none; detail=No confirmed C2PA AI assertion or SynthID watermark. Origin remains unresolved by these checks.
2. `model_agreement` synthetic=['Claude Vision', 'OpenAI Vision', 'Gemini Vision']; authentic=[]; uncertain=[]; forensic_supports_synthetic=False
3. `verdict` value=synthetic_likely; confidence=high; reason=3 models agree this is likely synthetic.
