## Prenatal Exposure to SARS and Birth Weight: Exploiting a Natural Experiment in Hong Kong

#### Research Statement 

- By exploiting SARS as an exogenous source of stress, this paper examines whether prenatal maternal exposure to such stress affects birth weight with the applicatin of OLS/ANOVA, Propensity Score Matching, and Bootstrapping.

#### Outline

- Introduction
- Background
  - SARS as a Public Health Crisis
  - Maternal Stress as Mechanisms
  - SARS as Exogenous Sources of Maternal Stress
- Literature Review
- Methods
  - Data
  - Variables
  - Models
    - Treat SARS as a Experiment (randomized)
      - OLS/ANOVA
    - Treat SARS as a Quasi-Experiment (non-randomized)
      - Propensity Score Matching
      - OLS/ANOVA
      - Bootstrapping
- Results
  - $Y_i = \alpha + \beta\space T + e_i$ where $\beta = E(Y_i^T - Y_i^C)$ is the Average Treatment Effect (ATE) 
- Discussion and Conclusion

#### PDF Preview

https://github.com/mingzhao1103/Stata_SARS/blob/main/report.pdf

*NOTE*
Difference-in-Differences ($DID$): the effects of treatment

  - $Y = \beta_0 + \beta_1 \space Treat + \beta_2 \space Time + \beta_3 \space (Treat*Time) + e_i$ where $\beta_3$ captures $DID$
       
  - $DID = (treatment_{after} - treatment_{before}) - (control_{after} - control_{before})$

  - Parallel Trends Assumption: the treatment group and the control group would follow equal trends over time.



