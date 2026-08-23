# Data

The modelling source is the **Society of Actuaries (SOA) 2014 Post-Level Term Lapse and Mortality Study**.

Official study page:
https://www.soa.org/resources/experience-studies/2014/research-2014-post-level-shock/

The SOA study page provides a ZIP archive containing the workbook **SOA Post-Level Term Lapse and Mortality Study.xlsx**, including the lapse and mortality pivot tables and the underlying study data used for custom analysis.

This project uses a lapse dataset reconstructed from the workbook's Excel Pivot Cache and saved locally as:

`soa_post_level_term_lapse.csv`

The reconstructed CSV is **not redistributed in this repository**. This keeps the repository lightweight and points users to the authoritative SOA source rather than publishing a derived copy of the study data.

To run the notebook, place the reconstructed file `soa_post_level_term_lapse.csv` in the repository root. The file is intentionally excluded by `.gitignore`.

## Local dataset shape

The reconstructed source contains 345,627 risk cells and 17 study variables (plus the exported CSV index column). After removing cells with zero policy-count exposure, 344,725 risk cells remain for analysis.

Each row represents an aggregated risk cell rather than an individual policy.
