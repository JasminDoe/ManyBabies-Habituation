# ManyBabies Habituation Analysis

## Overview
This repository contains the analysis, documentation, and outputs for the ManyBabies Habituation project. The study examines infant habituation using reproducible statistical methods implemented in R and Quarto.

## Repository Contents

- **MB_Habituation_Doenicke_20260321.qmd**  
  Quarto source file containing the full analysis, including data preparation, statistical modeling, and visualizations.

- **MB_Habituation_Doenicke_20260321.html**  
  Rendered output of the Quarto document.

- **ManyBabies Merged Data Dictionary.pdf**  
  Documentation describing the variables used in the merged dataset.

- **README.md**  
  Project documentation.

## Methods
The analyses include:

- Data preprocessing and descriptive analyses  
- Linear mixed-effects models  
- Spline-based regression models  
- Generalized Additive Models (GAMs)  
- Model comparison and evaluation  

## Requirements

### Software
- R (version 4.2 or later)
- RStudio
- Quarto

### R Packages
```r
install.packages(c(
  "tidyverse",
  "lme4",
  "lmerTest",
  "mgcv",
  "splines",
  "ggplot2",
  "readr",
  "dplyr",
  "tidyr",
  "knitr",
  "broom",
  "performance"
))
