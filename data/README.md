# Data Directory Guidelines

This directory contains configuration files and documentation for accessing the primary survey data used in this project.

## Dataset Details
* **Source:** Bangladesh Demographic and Health Survey (BDHS) 2022
* **Provider:** DHS Program / National Institute of Population Research and Training (NIPORT)
* **Data Level:** Individual Recode (IR) or Births Recode (BR) dataset

## Access Protocol
Due to DHS Program data distribution policies, raw dataset files (`.sav`, `.dta`, `.csv`) cannot be redistributed directly in this repository.

To set up the data locally:
1. Register for research access at the [DHS Program Portal](https://dhsprogram.com/data/dataset_admin/index.cfm).
2. Download the **BDHS 2022** dataset in Stata (`.dta`) or SPSS (`.sav`) format.
3. Place the downloaded raw data file inside this `data/` directory (e.g., `data/BDHS_2022_raw.dta`).

> **Note:** Raw dataset files (`*.dta`, `*.sav`, `*.csv`) are automatically ignored by `.gitignore` to prevent accidental public upload.
