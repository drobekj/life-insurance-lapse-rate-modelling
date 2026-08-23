# Portfolio export manifest

## Recommended core figures
1. `01_lapse_rate_by_duration` — strongest EDA/business-mechanism chart.
2. `02_duration10_lapse_rate_by_premium_jump` — directly shows the premium-jump mechanism at duration 10.
3. `03_temporal_validation_deviance` — main model-performance chart.
4. `04_temporal_validation_calibration` — main calibration/drift chart.

## Supporting figure
- `05_portfolio_lapse_rate_by_study_year` — useful context, but partly redundant with temporal calibration and therefore not essential for the README front page.

## Recommended core tables
- `final_results_summary` — primary compact portfolio/README table.
- `temporal_validation_folds` — full 8-fold out-of-time validation results.
- `temporal_stability_summary` — compact stability statistics across folds.
- `calibration_by_year` — detailed temporal calibration data.
- `glm_rate_relativities` — full GLM coefficient / rate-relativity table.
- `oof_calibration_summary` — aggregate OOF calibration.
- `final_holdout_summary` — untouched 2011-2012 holdout metrics.

## Supporting EDA tables
- `lapse_rate_by_study_year`
- `lapse_rate_by_duration`
- `duration10_premium_jump_summary`

CSV files preserve numeric values. Markdown files are convenient for GitHub/README reuse.
PNG files are intended for normal README/web use; SVG files are included for scalable reuse.
