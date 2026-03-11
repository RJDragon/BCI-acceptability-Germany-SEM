# Predictors of Behavioural Intention regarding BCIs in Rehabilitation

This repository contains the complete R analytical workflow for a study investigating the factors that explain individuals’ intentions to use Brain-Computer Interfaces (BCI) in stroke rehabilitation. 

The study applies and extends the theoretical framework proposed by **Grevet et al. (2023)** to a German-speaking sample.

## 🔗 Preregistration
The design and analysis plan for this study were preregistered on OSF:  
[https://osf.io/xysjv/](https://osf.io/xysjv/)

## 📋 Study Overview
- **Objective:** To identify key predictors of Behavioral Intention (BI) using an adapted Technology Acceptance Model (TAM3).
- **Methodology:** Structural Equation Modeling (SEM) and Confirmatory Factor Analysis (CFA).
- **Planned Sample:** N=588 German-speaking participants (recruited via Prolific).
- **Key Variables:** Behavioral Intention (BI), Perceived Usefulness (PU), and Perceived Ease of Use (PEOU), alongside 13 latent predictor factors.

## 💻 Analytical Workflow
The analysis is implemented in R and covers:
1. **Data Preprocessing:** Cleaning, reverse coding, and merging of age-group datasets.
2. **Exclusion Criteria:** Implementation of attention-check and video-viewing filters.
3. **Descriptive Statistics:** Demographic summaries and variable distributions.
4. **Measurement Models:** Two CFAs to validate the 16-factor structure.
5. **Structural Model:** SEM estimation using factor scores for parsimony.
6. **Hypothesis Testing:** Mediation analysis (bootstrapping), Welch t-tests (German vs. French sample), and paired-sample t-tests (Pre- vs. Post-video intervention).

## 📂 Repository Structure
* `GitHub_Thesis_BCI.Rmd`: The primary R Markdown file containing all code.


## 🛠️ Usage
To reproduce the analysis:
1. Clone this repository.
2. Ensure you have the following R packages installed:
tidyverse, readxl, lavaan, semTools, semhelpinghands, stringr, knitr, kableExtra, gt, purrr, ggforce, BayesFactor, writexl, semPlot, ggplot2, dplyr, patchwork, gridExtra
3. Open the R project and knit `GitHub_Thesis_BCI.Rmd`.
