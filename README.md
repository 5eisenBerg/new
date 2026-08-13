# Overleaf Upload Package (V76)

This zip is ready to upload to Overleaf.

## Files
- `main.tex` — full conference-style manuscript (Springer LNCS/LNEE-safe format)
- `references.bib` — bibliography entries
- `tables/table_results.tex` — main quantitative table
- `tables/table_stats.tex` — statistical significance table
- `figures/*.png` — all figures referenced in the manuscript
- `artifacts/raw_results_v76.csv` — raw evaluation results
- `artifacts/training_log_v76.csv` — training trace
- `artifacts/final_results_v76.xlsx` — exported summary

## Overleaf compile settings
- Compiler: `pdfLaTeX`
- Bibliography tool: `BibTeX`
- Class/template: Springer proceedings (`llncs` / LNEE workflow)

## Notes before submission
- Replace affiliation/email placeholders in `main.tex` when final author details are available.
- The source now targets single-column Springer-safe formatting and uses cleaner PDF metadata fields.
- If Overleaf reports missing `llncs.cls`, create a project from Springer LNCS template first, then replace its `main.tex` content with this manuscript.


https://jaipur.manipal.edu/event-details.php?url=586/4th-international-conference-on-intelligent
