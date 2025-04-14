# NHANES-phthalates

# Phthalates and Antibody Response

This repository contains the R Markdown analysis and supporting code for the thesis project exploring the association between phthalate exposure and the immune response to vaccination in a pediatric American population.

## Project Description

The analysis investigates how phthalate concentrations in urine relate to antibody levels against specific vaccines. 
Several statistical approaches were applied to assess both linear and complex nonlinear relationships, accounting for potential confounders such as age, sex, income, and ethnicity.

## Methods Used

- **Linear Regression**  
  To evaluate the direct associations between individual phthalate metabolites and antibody concentrations.

- **Quantile G-Computation (qgcomp)**  
  A robust method to estimate the joint effect of multiple exposures acting as a mixture.

- **Bayesian Kernel Machine Regression (BKMR)**  
  Used to explore potential nonlinear and interactive effects among phthalates in relation to immune response.

- **Bayesian Factor Analysis**  
  Applied to reduce dimensionality and identify latent factors that may represent underlying exposure patterns.

## Files

- `phthalates_analysis.Rmd`: Full R Markdown script including data preprocessing, modeling, and result visualization.
- `README.md`: This file.

## Requirements

- R (>= 4.2)
- R packages: `qgcomp`, `bkmr`, `infinitefactor`, `ggplot2`, `dplyr`, etc.

## Note

Replace 'your/path/to/data/folder/' with your actual file path before running the script.

## Author

**Michele Salerno**  
Visiting Researcher – Department of Environmental Medicine & Public Health  
Icahn School of Medicine at Mount Sinai, New York, NY  
Master degree in Biostatistics – University of Milano-Bicocca
