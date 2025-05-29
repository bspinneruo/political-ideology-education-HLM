# Political Ideology and Academic Achievement: A Multilevel Modeling Analysis

## 📊 Objective

This project investigates whether county-level political ideology, measured as average Republican vote share from 2008–2016, is associated with standardized academic achievement across U.S. counties. The analysis employs both frequentist and Bayesian multilevel models to account for the hierarchical structure of counties nested within states.

---

## 🧰 Tools & Methods
- **Statistical Software**: R  
- **Modeling Frameworks**: `lme4` (frequentist) and `brms` (Bayesian)  
- **Data Wrangling**: `tidyverse`, `dplyr`  
- **Visualization**: `ggplot2`, `sjPlot`  
- **Modeling Techniques**:  
  - Multilevel linear models (random intercepts and slopes)  
  - Uncertainty-weighted Bayesian model  
  - Intraclass correlation (ICC), variance decomposition  

---

## 📂 Data Sources
- **Stanford Education Data Archive (SEDA)**: Academic achievement outcomes  
- **MIT Election Lab**: County-level Republican vote share (2008–2016)  
- **U.S. Census (ACS)**: Demographic covariates (e.g., poverty, SES, urbanicity)

---

## 🔑 Key Variables
- **Outcome**: Standardized academic achievement (county average)  
- **Predictor**: Avg. Republican vote share (continued study with time lagged)  
- **Covariates**: SES, poverty, urbanicity, BA attainment, SNAP, single-mother households  

---

## 📈 Key Findings
- Counties with higher Republican vote share showed slightly higher achievement, controlling for key SES and demographic factors (This is preliminary and further analysis is underway accounting for time and clustering within states)
- Substantial between-state variance (ICC ≈ 0.40)  
- Bayesian models supported findings with robust posterior intervals  
- Model fit improved with random slopes for ideology effects across states  

---

## 🎯 Relevance to Industry
This project demonstrates:
- Hierarchical and causal modeling across nested data  
- Integration of public policy and education datasets  
- Replicable analysis pipeline aligned with experimentation frameworks  
- Strong data storytelling for decision support and product strategy  

---

## 📎 Files Included
- `hlm_political_ideology.Rmd`: Full analysis in R Markdown   

---
