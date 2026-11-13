# Validation status (model v2.1)

Testing was AI-assisted with limited independence; LibreOffice 24.2 only.

| Status | Count | Defects |
|---|---|---|
| Fixed and retested | 7 | D-01, D-02, D-03, D-04a, D-05, D-06, D-07 |
| Implemented; not testable here | 3 | D-04b, D-08, D-10 |
| Implemented; LibreOffice tested; Microsoft Excel verification pending | 2 | D-09, D-11 |
| Descoped (source data unavailable) | 1 | D-12 |

12 defects in total; D-04 is counted as D-04a and D-04b.

- Live QA checks: 85 (original), 97 (v2), 106 (v2.1); all pass in LibreOffice.
- All 27 original scenario runs were re-run; 17 unrelated to a defect are identical to the originals.
- A 5% price-cut test gave EBITDA of (4.51) under the original cost method and (27.72) under the corrected one.
- Dashboard tests: 15 cases in LibreOffice. The analyst dashboard cut-off warning screenshot shows a deliberate test (a December cut-off requested although actuals exist through October); the "1 check failing" status there is intended behaviour.
