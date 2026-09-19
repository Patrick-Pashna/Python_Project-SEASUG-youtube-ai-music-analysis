# Fresh analysis workspace

This project is intentionally reset to a clean slate. Keep the raw data in data/raw and rebuild all derived outputs from scratch.

## Structure
- data/raw: original source data only
- data/processed: cleaned / engineered datasets
- src: analysis scripts
- outputs/models: trained models and metadata
- outputs/tables: tables and summary results
- outputs/figures: figures and plots
- notebooks: exploratory analysis notebooks
- logs: run logs and diagnostics

## Rule
Do not reuse old processed data or previous model outputs unless you are intentionally comparing them as a separate baseline.
