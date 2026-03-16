# PISA Education Outcomes Analysis

This project analyzes educational outcomes using PISA 2022 data across eight countries.  
The analysis was conducted in R as part of a Quantitative Research Methods project.

## Research Question

How do factors such as reading ability, language spoken at home, ICT resources, and socioeconomic conditions affect student mathematics performance?

## Methods

The project applies several econometric techniques:

- Data standardization (z-scores)
- Descriptive statistics
- Data visualization
- OLS regression
- Multivariate regression
- Interaction models
- Instrumental variables (IV) estimation
- Heteroskedasticity-robust standard errors

## Tools

Analysis performed in:

- R
- dplyr
- ggplot2
- modelsummary
- sandwich
- lmtest
- AER
- flextable

## Key Findings

- Reading ability is strongly correlated with mathematics performance.
- Access to ICT resources is positively associated with student outcomes.
- Socioeconomic conditions such as food availability influence academic performance.
- Instrumental variable analysis suggests the ICT-performance relationship is likely associative rather than strictly causal.

## Repository Structure
pisa-education-outcomes
│
├── pisa_case_analysis.R
├── report/
│   └── QRM_III_PISA_Education_Outcomes.pdf
├── figures/
│   ├── score_distributions.png
│   ├── reading_math_correlation.png
│   └── interaction_effects.png

## Data

The raw dataset is not included in this repository.  
Please obtain the original PISA dataset separately before running the analysis.

## Author

Kevin Pinto  
Vrije Universiteit Amsterdam – Economics
