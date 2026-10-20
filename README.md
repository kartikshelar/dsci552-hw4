# Homework 4 — Time Series Classification (AReM)

DSCI-552 (Machine Learning for Data Science) — Homework 4.

## Structure

```
.
├── README.md
├── requirements.txt
├── Homework4.pdf
├── AReM.zip
└── Shelar_Kartik_HW4.ipynb
```

## Contents

- `AReM.zip` — Activity Recognition system based on Multisensor data fusion
  (AReM) dataset (UCI): 88 instances across 7 activities, each with 6 time
  series of 480 values. The notebook reads it directly from the zip.
- `Shelar_Kartik_HW4.ipynb` — full analysis: time-domain feature extraction
  (Homework 3 rerun), binary classification of bending vs. other activities
  with logistic regression (RFE and L1-penalized), case-control sampling,
  multiclass classification with L1-penalized multinomial regression and
  Naïve Bayes, and ISLR 4.8.3 and 4.8.7.
- `Homework4.pdf` — assignment.

## Setup

```bash
pip install -r requirements.txt
```

Then open `Shelar_Kartik_HW4.ipynb` in Jupyter, keeping `AReM.zip` in the same
folder. A full run takes about 25–30 minutes, mostly the cross-validation
searches over the number of segments.
