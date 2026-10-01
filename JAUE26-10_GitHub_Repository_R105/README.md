# Coccinellid abundance and short-horizon aphid forecasting: reproducibility materials

**Version:** R105  
**Prepared:** 30 September 2026  
**Related manuscript:** *Current Coccinellid Abundance Provides Limited and Inconsistent Gains in Short-Horizon Aphid Forecasts: A Reanalysis of Three Public Soybean and Wheat Datasets*

## Purpose

This repository contains supporting documentation for a secondary analysis of three publicly available aphid–coccinellid datasets. The analysis asks whether coccinellid abundance recorded at a scouting visit improves prediction of aphid abundance at a subsequent visit beyond aphid-only models and a persistence forecast.

The repository is designed to provide the technical material that is not carried in the journal article. It does **not** redistribute third-party raw observations.

## Source datasets

The original observations remain with their source repositories:

- Wisconsin soybean survey — Dryad: https://doi.org/10.5061/dryad.2547d7wwt
- Indiana soybean survey — KNB: https://doi.org/10.5063/F15T3HPK
- Wheat experiment — Dryad: https://doi.org/10.5061/dryad.2fqz612x5

These external datasets retain their original repository terms and licenses.

## Repository contents

- `technical_appendix/JAUE26-10_Repository_Technical_Appendix_R105.docx`  
  Extended source reconstruction, model comparisons, resampling diagnostics, support checks, and sensitivity analyses.

- `dataset_selection/JAUE26-10_Dataset_Selection_Register_R105.csv`  
  Dataset inclusion/exclusion register used to document why the three source datasets were selected.

- `DATA_SOURCES.md`  
  Source-data and redistribution boundary.

- `CITATION.cff`  
  Machine-readable citation metadata for this repository.

- `CHANGELOG.md`  
  Version history for the repository materials.

- `LICENSE_NOTICE.md`  
  Licensing notice. No third-party raw data are licensed or redistributed here.

- `archive_pending/README_ADD_R104_ANALYSIS_ARCHIVE.md`  
  Records the one item that must still be added from the original R104 submission archive for a complete code-and-output reproducibility deposit.

## Important completeness note

The original JAUE submission email included `Analysis_Code_Derived_Outputs_R104.zip` (712,844 bytes). Its bytes were not available in the current revision workspace, so this GitHub package does **not** claim that the analysis code or frozen numerical outputs are included yet.

Before describing this repository as a **complete reproducibility archive**, add the original R104 analysis archive (preferably unpacked into clearly named folders) or revise the manuscript so that it does not claim public availability of code and derived outputs.

Suggested structure after adding the R104 archive:

```text
01_code/
02_source_hashes/
03_derived_ledgers/
04_fixed_predictions/
05_numerical_checks/
06_figures/
07_technical_appendix/
08_dataset_selection/
archive/
```

## Scientific boundary

The repository supports a bounded secondary reanalysis. It does not establish biological-control efficacy, an insecticide threshold, a transferable crop effect, or independent external validation of a universal forecasting model.

## Suggested citation

Li, X., Guo, B., & Kartanova, A. (2026). *Coccinellid abundance and short-horizon aphid forecasting: reproducibility materials* (Version R105). Public GitHub repository.

After a GitHub Release or DOI-bearing archive is created, replace the generic repository wording above with the final release URL or DOI.
