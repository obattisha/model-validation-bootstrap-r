# model-validation-bootstrap-r

R problem set on model validation strategies and bootstrap resampling, applied to predicting political attitudes from survey data.

## Topics covered

- Ordinary Least Squares (OLS) regression
- Full-dataset MSE evaluation
- 50/50 train-test holdout validation
- 1,000 repeated random train-test splits
- Bootstrap resampling (B = 1,000) for parameter estimates and standard errors

## Data

**2008 American National Election Studies (ANES)** — `nes2008.csv`

The outcome variable is the Biden feeling thermometer score (0-100), measuring respondents' warmth toward Joe Biden. Predictors include age, gender, education, party identification, and political ideology.

## Files

- `problem-set-2.Rmd` — full R solution with all four validation approaches
- `problem-set-2.pdf` / `ps2.pdf` — rendered output
- `nes2008.csv` — 2008 ANES survey data

## Requirements

R with packages: `ggplot2`, `tidyverse`, `modelr`, `rsample`
