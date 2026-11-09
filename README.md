# Warranted Reliance and Uncertainty in AI

Reproducible computational study examining how predictive evidence,
decision costs, distribution shift, and limited review affect reliance
on AI recommendations.

## Authors

- Harshal Tittamelanahalli Venkatesh
- Sagar Vig

Group 18 — Mission Possible  
Project 15 — Warranted Reliance and Uncertainty

## Research questions

1. Under what combinations of error and deferral costs do
   confidence-based and cost-aware policies prescribe different actions
   for identical model predictions, and how do these differences affect
   decision loss and automated coverage?

2. How does finite-sample uncertainty in estimated predictive reliability
   affect the stability of reliance decisions, and when does incorporating
   that uncertainty improve decisions compared with point estimates alone?

3. Under what changes in population composition does a previously validated
   reliance policy become unreliable, and to what extent can recalibration
   restore its decision performance without retraining?

4. When does abstention reduce automated prediction error while increasing
   subgroup disparities in deferral burden, and how do limited review
   capacity and imperfect fallback decisions affect this trade-off?

## Repository contents

| File | Description |
|---|---|
| notebook54259d8109.ipynb | Executed Kaggle notebook with code, explanations, and displayed results |
| Project15_Revised_Results.zip | Figures, tables, predictions, captions, configuration, and provenance records |

The completed run contains 29 executed code cells and 24 primary result
objects: 12 figures and 12 tables. The results archive contains 129 files.

## Datasets

The prediction tasks are analyzed separately.

- UCI Default of Credit Card Clients: 30,000 records.
- ACSIncome, Delaware 2018: 4,713 eligible records.
- ACSIncome, Maryland 2018: a bounded sample of 12,000 records.
- ACSIncome, Delaware 2019: 4,755 eligible records.

Sources:

- https://doi.org/10.24432/C55S3H
- https://github.com/socialfoundations/folktables
- https://www.census.gov/programs-surveys/acs/microdata.html

Original dataset terms and attribution requirements remain applicable.

## Running the notebook

1. Download the notebook and import it into Kaggle.
2. Select CPU; no GPU is required.
3. With Internet enabled, the loader can download the source data.
   For offline execution, attach the original UCI file and ACS files
   using the filenames and year-specific folders documented in the notebook.
4. Run all cells from the beginning.
5. Confirm the final message reports:
   `Validated: 24 primary results`.
6. Download `Project15_Revised_Results.zip` from the output directory.

The notebook uses Python, NumPy, pandas, matplotlib, scikit-learn,
and an Excel reader. Runtime versions are recorded in the results archive.

## Interpretation and limitations

This is an exploratory computational study, revised following pilot analysis.

Error costs, deferral costs, fallback performance, and review capacity
are explicitly constructed scenarios. The datasets do not measure
psychological trust, actual human review performance, or institutional harm.

The uncertainty-aware policy frequently defers every case and does not
consistently improve realized test loss. Null and unfavorable results
are retained.

Successful execution does not establish novelty, moral justification,
or journal publication readiness.

## Target journal and anchor paper

Target journal: Minds and Machines, Springer Nature.

Ferrario, A. (2026). Being Pragmatic About Reliance and Trust in
Artificial Intelligence. Minds and Machines, 36, Article 5.

https://doi.org/10.1007/s11023-025-09754-9

## Archival citation

A Zenodo DOI will be added after the repository is connected to Zenodo
and a versioned GitHub release is archived.# Project15-warranted-reliance
