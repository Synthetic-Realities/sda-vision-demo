# SDA Vision 0.1.1: release acceptance

29 September 2026. Dr Sam Martin authorised publishing the Google Lens scope and Reflect layout fixes across GitHub, the installation pack and the existing Zenodo software series.

## Exact software archive

- File: `SDA_Vision_0.1.1_source.zip`
- Public-source commit: `edf5aba1c04cc97df4cd12752fe473db96c96741`
- SHA-256: `21b8b27db260a2ba9c8a17992a6750c10a9018bd00ce404bfad659aac49f5aa1`
- MD5 (transfer check): `ac141d2c5d57ebe9e6958b72c1ae2348`
- Version DOI: `10.5281/zenodo.23039037`.
- Software Concept DOI: `10.5281/zenodo.23008102`.

The ZIP contains this commit's public source and built Research interface. Its `ARCHIVE_MANIFEST.json` records 388 file hashes, excluding itself. The original 0.1.0 archive and version DOI remain preserved.

## Checks

| Check | Result |
| --- | --- |
| Offline Python regression suite | 341 passed; two dependency deprecation warnings |
| TypeScript | Passed in private and public source checkouts |
| Production builds | Public, Research, Conference, workshop and installation passed |
| Browser workflows | 60 scenarios passed: five builds, 390/1440-pixel widths, image/PDF/podcast/slides/video selections |
| Reflect | Findings and Evidence box initially collapsed; keyboard reopening, retained notes, repeat Check/Reflect navigation and visible session actions passed |
| Google Lens | Available for image originals; absent for non-image formats; original downloads remain available; image-preview isolation passed |
| Citation checks | All-media citation regression passed; saved records remain unchanged |
| ZIP and manifest | ZIP integrity and all file hashes passed |
| Release hygiene | Credentials, private guidance, participant data and development Git history excluded; secret-pattern scan passed |
| Fresh installation from this ZIP | Native Apple Silicon Python 3.12.14; hash-locked dependency installation, pip check, npm ci and frontend rebuild passed |
| Clean startup | Installed launcher chose localhost:8101; reports version 0.1.1, eleven approved originals and unconfigured model providers |
| Freshly rebuilt interface | 12 further browser scenarios passed for image-search scope and Reflect, at desktop and phone widths |
| Paid inference / external media uploads during checks | 0; analysis calls were mocked |

The public-source packaging allowlist references the files shipped in the public repository. The first regression pass found obsolete references to excluded preparation records; correcting that list retained the strict missing-file and unsafe-symlink checks, and the complete suite then passed. The fresh frontend uses root asset paths; its browser test served those paths to match installed operation.

The facilitator guide remains version 1.4. Provider prompts, agreement rules, trust policy, original media and saved analyses are unchanged. Software 0.1.1 identifies this interface release; saved reports retain their original software and method versions.

This pass covers installation on this Apple Silicon Mac and browser checks at desktop/phone widths. Physical phones, Amazon Silk, the conference projector, Windows, Linux and Intel Mac installation were not retested. Earlier researcher-reported physical-device checks remain in the 0.1.0 record.

The new software draft belongs to the original Zenodo series through its **New version** action. No GitHub-to-Zenodo release webhook is enabled. Publication follows these checks; the accompanying published record supplies its final status.
