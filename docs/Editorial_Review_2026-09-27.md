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

## Repository audit scope

The audit started from the researcher's committed edits: private `75ce95e` and
public `92f5e2d`. Their revised verdict, launch, health-lens and privacy sections
were preserved; the duplicate privacy link was removed and the remaining
introductory copy was aligned with them.

| Surface | Review outcome |
|---|---|
| Private README, privacy and security | Purpose and processing first; retained recipients, consent, retention and status boundaries. Added the agreed ORCID link. |
| Public README and About | Invites exploration; explains prepared results, browser-session notes, external services and host privacy. |
| Workshop and external checks | Replaced repeated “needs human review” with source/context comparisons; kept status distinctions and manual attachment choices. |
| Session downloads | Updated app-owned scope text; original provider replies, findings and notes remain intact. |
| Release and Conference guidance | Clear actions and current configuration; corrected stale descriptions of implemented note entry and the Conference profile. |
| Example inventory | Clarified eleven private preparation examples versus ten public examples; media bytes and credits unchanged. |
| Saved reports, graphs and prepared exports | Reviewed as historical research records; retained verbatim. |
| Method, acceptance, capability and compatibility records | Retained dated evidence and uncertainty; current entry-point guides link to this review. Historical capability statements are not a fresh vendor assessment. |
| Code, configuration, prompts and tests | Reviewed wording surfaces; processing rules, model prompts, consent controls and structured statuses unchanged. Existing wording assertions updated with their underlying safety checks retained. |
| Licences, third-party notices and rights terms | Retained exactly. The scope document's obsolete contribution-guide link was removed; its terms were preserved. |
| Local guidance | Removed AGENTS.md and CONTRIBUTING.md from current tracked files and the package allowlist at the researcher's request; local workspace copies retained. |

## Packaging correction

The full check exposed an existing package-builder error: directories with no
filename extension were being selected alongside extensionless licence files.
The builder now skips ordinary directories, retains the notice files and
continues to reject symlinks. A regression check covers that distinction and
the exclusion of local guidance. This is a packaging repair, separate from
scientific method and copy revisions.

The earlier commits in the private repository remain historical Git records;
removing a file from the current tree does not erase its earlier versions.

## Editorial references

Privacy wording was checked against ICO guidance on
[controller and processor roles](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/controllers-and-processors/controllers-and-processors/),
[special-category data and DPIAs](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/lawful-basis/special-category-data/what-are-the-rules-on-special-category-data/),
and [publicly available personal data](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/individual-rights/the-right-to-be-informed/what-common-issues-might-come-up-in-practice/).
This review changes explanatory language; institutional decisions remain in
the approved processing record.

## Workshop presentation — current behaviour

Display/workshop revision: `workshop-flow-2026-09-27.1`.

Community Workshop and Facilitator use a bold, black Start here heading. The
opening illustration has an exact-file saved analysis covering Claude, OpenAI
and Gemini readings. Its Notice, Discuss, Check and Reflect activities share the
current response. The ten menu examples and their set graph form a separate set.

Discuss offers media-specific observations. Check presents recorded findings;
image/file history and C2PA details sit within Provider evidence and ratings.
Response-storage information is in About/privacy guidance and the reset dialog.
The compact footer provides credits, repository and privacy links. The [workshop guide](Workshop_Activities_2026-09-25.md)
describes controls, response handling and downloads.

Scientific method and raw saved reports retain their recorded versions. Model
inference is outside this display revision. Physical-device and native-download
acceptance is recorded separately from automated and browser checks.

The findings overview and Evidence box each span the workshop page width. Provider evidence and ratings brings together model readings, supporting and additional findings, and the expandable file-history record. The footer groups credits, repository and privacy links.

Verification for this display revision: 27 focused Python checks, research/public workshop render checks, community export helpers, TypeScript and both builds passed. Browser review covered the opening four-step journey, both workshop views, preserved responses, C2PA detail, podcast sound scope and phone/desktop widths. Physical-device and native-download acceptance remains with the researcher. The Facilitator tab remains available while the illustrated guide is reviewed.
