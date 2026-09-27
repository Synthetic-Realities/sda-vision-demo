# Copy review — 27 September 2026

Copy revision: `editorial-2026-09-27.1`. Analysis method:
`pdf-preparation-2026-09-26.1` (unchanged).

## Purpose and changes

The researcher requested prose that introduces the purpose of each feature,
describes its actual coverage and invites informed review. The current copy
reduces repeated disclaimers and replaces general prohibitions with concrete
choices, processing facts and useful next steps.

The About page, README, privacy footer, external-check guidance and workshop
summaries now follow that approach. Explicit limits remain beside the relevant
check: Inconclusive, unavailable and failed results stay distinct; ratings are
not calibrated probabilities; sound-origin detection remains outside the
workflow; graphs retain “Distribution history: not assessed”.

The website continues to use ten prepared examples and saved findings. Every
original, saved report, prepared export, graph and media-credit file remains
byte-identical. Earlier results may therefore retain their original wording.
Session export labels use the current copy while preserving the recorded analysis
and separately entered notes. This revision makes no new provider requests.

## Verification

- Offline Python checks: 313 passed, with two existing dependency deprecation warnings.
- TypeScript and research/public production builds passed.
- Community presentation checks passed, including failed/unchecked/inconclusive
  states, sampling, provenance, response inclusion and report immutability.
- PDF/PPTX/CSV export-font checks passed with the original report unchanged.
- Browser checks confirmed Community Workshop as the default, ten choices,
  the revised recorded-finding summary, privacy text and About page. The
  390-pixel viewport had no horizontal overflow or file-upload inputs.
- The rebuilt site contains 272 files; prepared examples and results retain
  their previous hashes. Method rules, consent controls and dependencies are unchanged.

These are software and browser-viewport checks. Physical-device, projector,
browser file-saving and native presentation-software rehearsals remain to follow.

Local collaboration and contribution guides are excluded from the current
repositories and release package. The public demo contained neither guide.
The full source remains private; this update publishes revised demo copy.

## Workshop opening update — 27 September 2026

Display/workshop revision: `workshop-start-2026-09-27.1`.

The Community Workshop and Facilitator example picker now starts with a large,
bold, black “Start here” heading. The opening illustration supports first
impressions and workshop notes, with image-specific choices. Its existing
AI-generated attribution remains visible. Choosing an example starts a fresh
response; switching presentation keeps the current response. The new-session
control also resets a session that started with the opening illustration.

Session summaries name the opening illustration and can include its preview.
Recorded analyses still require a selected example. The Showcase footer now reads:
“Showcase — saved results for the included examples. Coverage and analysis dates
are recorded with each result.”

Verification: TypeScript and research/public builds passed; workshop-start render
regressions and community/export helper checks passed. Browser checks covered
both views, initial response entry, busy controls, new-session reset, choosing the
podcast with a fresh response, the exact footer, absent upload controls and a
390px viewport without horizontal overflow. The CSV action reached its download
started status; native file receipt was not confirmed by the browser tool.
Physical-device and native download checks remain on the morning test table.

Scientific method, saved reports and original media are unchanged. No new provider
calls were made. The full source repository remains private.
