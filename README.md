# IOTC WPTT 2026 – Skipjack tuna (SKJ) Stock Assessment (SS3) 🎣

Code and model files for the 2026 Indian Ocean Tuna Commission (IOTC) Working Party on Tropical Tunas (WPTT) skipjack tuna stock assessment, run in Stock Synthesis (SS3).

The repository covers the full workflow (some plots or graphing are excluded to allow the user to use their own scripts, and for (some) brevity):

- Data preparation
- Base model runs
- Sensitivity runs
- Model diagnostics
- Model grid (ensemble)

## Requirements

- **Stock Synthesis (SS3) v3.30.25.1**
- **R** (all required packages are loaded at the top of each script, so install any that are missing when prompted)

## Getting started

1. **Get the repository.** Either download the `main` branch, or, if starting from scratch, recreate the same directory structure (see below).
2. **Set your base path.** Edit the base path in the `init.R` file. There is an `init.R` in several directories, so update each one.
3. **Run the analyses in order**, following the numbered folder prefixes (`1_dataprep`, then `2_modelruns`, then `3_diagnostics`, then `4_gridrun`).

## Repository structure

| Folder | Description |
|--------|-------------|
| `1_dataprep` | Data preparation scripts |
| `2_modelruns` | 2026 SS3 model runs (base model and sensitivities) |
| `3_diagnostics` | Model diagnostics |
| `4_gridrun` | Model grid runs |
| `data` | Input data |

### Running the grid and diagnostics

The grid (`4_gridrun`) can be run before the diagnostics (`3_diagnostics`). If you run the diagnostics first, you will need to make sure the grid diagnostics are commented out ("hashed out").

## Data

Data can be found in the relevant folders in "data". Note that these are the data used in the 2026 assessment. For the latest datasets, please check the IOTC webpages, or contact the Secretariat.
Tagging data are not included in the datasets - these contain confidential information (e.g. location of individual vessels). To access these data, please contact the Secretariat.

## Contact

Genevieve Phillips – Genevieve.Phillips@fao.org
IOTC Secretariat - IOTC-Secretariat@fao.org


