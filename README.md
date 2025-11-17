Group09:
Selina Friesen - s252027
Marta Sanchez Sanchez - s254791
Sergi Fornos - s253693
Tommaso Ballocci - s257151
Ivan Musalyk - s225210

## Project Overview
This repository implements the required R4BDS project structure.

The project analyses epitope-level CD8 T cell responses against SARS-CoV-2,
based on the dataset from Saini et al., Sci Immunol 2021.

## Data Retrieval
Raw data are NOT stored on GitHub.

Place the raw data file(s) in:

- `data/_raw/raw_data.xlsx`

or adapt the file name and path in `R/01_load.qmd`.
If programmatic retrieval is possible, implement it in `01_load.qmd`
and describe access in a safe way.

## Project Structure

- `data/_raw/` – raw, untouched data
- `data/01_dat_load.tsv` – loaded / combined data
- `data/02_dat_clean.tsv` – cleaned, tidy data
- `data/03_dat_aug.tsv` – data with derived variables

- `R/01_load.qmd` – load raw data
- `R/02_clean.qmd` – clean and tidy data
- `R/03_augment.qmd` – add derived variables
- `R/04_describe.qmd` – descriptive statistics
- `R/05_analysis_1.qmd` – first main analysis
- `R/06_analysis_2.qmd` – second main analysis
- `R/99_proj_func.qmd` – helper functions
- `R/00_all.qmd` – master document to orchestrate the full pipeline

- `results/` – HTML outputs and key plots
- `doc/presentation.qmd` – final Quarto presentation
- `doc/presentation.html` – rendered self-contained presentation

## Presentation Link
Add the direct link generated with raw.githack, for example:

https://raw.githack.com/<org>/<repo>/<branch>/doc/presentation.html
