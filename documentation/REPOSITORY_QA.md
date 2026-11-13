# Repository QA

Checks run when this repository was packaged (14 November 2026). Self-checks by the same AI assistant that built the content; not independent review.

| Check | Result |
|---|---|
| Workbook copies: disclosure rows added as text only | 11 workbooks edited by direct XML edit so charts are preserved |
| Each edited workbook recalculated in LibreOffice and compared with its original | 0 formula errors; every value matches (model v2.1: 34,056 cells compared, 0 differences) |
| Charts preserved | Model v2.1: 12 of 12; ROI and TCO model: 3 of 3 |
| Originals unchanged | Yes; only copies were edited |
| Superseded, obsolete, duplicate and temporary files | Excluded (see FILE_MAPPING.md); no duplicate files by content hash |
| Local paths, credentials, e-mail addresses, API keys | None found in repository text, workbook, document or presentation content |
| File names | No spaces or ampersands |
| Markdown links | All relative links resolve |
| Phase 1 report | Kept only in `historical/` with a warning line; content unchanged |
| Scripts | Not published. Some documents cite script names (for example indep.py, recalc.py) as test methods only |
| Microsoft Excel | Not tested |
| Inputs | Two original inputs copied unedited (byte comparison done for the brief) |
| Archive | Stage 4F case study kept in `archive/`, labelled superseded |
| Model Phase 1 warning | Warning row added to the model's QA_Recon sheet after issue I-04 (historical, superseded, unreconciled; v2.1 is the version of record; no explanation asserted). Recalculated: values unchanged, charts 12 of 12 |
