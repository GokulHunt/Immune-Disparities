# Immune-Disparities
Looking into regional differences in immune cell populations in the US Health and Retirement Study.

### Analysis Summary
The primary objective of this study was to examine regional variations in immune cell subsets and ARIPs based on three geographic factors: current residence in the South vs. non-South, birthplace in the South vs. non-South, and relocation patterns. In addition, we examined differences in immune cell subsets across the four U.S. Census regions for both current residence and birthplace.

#### Statistical Methods Used
Linear outcomes (immune cells): **Two-level linear regression models** for continuous immune markers, accounting for clustering of individuals within census tracts

Categorucal outcomes (ARIPs): Logistic regression models with standard errors adjusted for census tract clustering

**Sampling weights were used**, hence the estimates are nationally representative.

All models were adjusted for covariates, including age, sex, race/ethnicity, educational attainment, smoking status, BMI, comorbidity index, CMV seropositivity, and white blood cell count. 
