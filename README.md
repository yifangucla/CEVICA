# CEVICA

CEVICA, Cooking Energy and Ventilation Impacts on Children with Asthma, is a collaborative research study examining how cooking energy, kitchen ventilation, and related exposure reduction interventions affect indoor air quality and respiratory health in homes of children with asthma in California's Central Valley.

The study is funded by the California Energy Commission and is conducted by a research team from Lawrence Berkeley National Laboratory, Central California Asthma Collaborative, University of California San Francisco, University of California Los Angeles, and Association for Energy Affordability.

## Repository status

This private repository is being prepared for the release of CEVICA data processing, quality assurance, quality control, event detection, and analysis code. The directory structure is available, but no study code or participant level data have been added.

## Repository structure

| Directory | Purpose |
| --- | --- |
| `01_data_preparation` | Data download, tidying, cleaning, and merging for HA and Sapiens data |
| `02_no2` | NO2 quality control and event detection |
| `03_pm25` | PM2.5 quality control and event detection |
| `04_cooking` | Cooking data quality control and event detection |
| `05_range_hood` | Range hood data quality control and event detection |
| `06_analysis` | Statistical analysis, sensitivity analyses, tables, and figures |

`01_data_preparation` is divided into `download`, `tidy_clean`, and `merge`. Each section contains `scripts`, `docs`, and `examples`.

The NO2, PM2.5, cooking, and range hood sections are divided into `qaqc` and `event_detection`. Each section also contains `scripts`, `docs`, and `examples`.

The analysis section contains `scripts`, `docs`, and `examples`. Analysis code should read outputs from the earlier processing sections and should not redefine quality control or event detection rules.

## Data privacy

Study data are not public and are not included here. Participant data, credentials, restricted project files, and participant level outputs must not be added to this repository. Examples must use synthetic data that do not represent real participants.

## Citation and license

Citation information will be added after the related methods and results are published. No open source license has been selected. All rights are reserved until the CEVICA project team approves a license.
