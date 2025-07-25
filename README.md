# Regional Disparities in Waste Management: A Bayesian Analysis of Italian Municipalities

---

## Abstract


This study investigates municipal waste management in over 4000 Italian municipalities trying to understand how consumers’ waste habits are influenced by their income, different types of paying fees and different socioeconomic context in different parts of Italy. The analysis was conducted using data from the Bicocca Open Archive Research Data (BOARD) that includes geographical, economic, demographic, and waste management variables and applying **Bayesian** models by treating the geographical areas both as a sample of a broader, underlying population and as three distinct, unchangeable, and exhaustive divisions of Italy. The results from these Bayesian approaches were then compared with those obtained from **frequentist** methods, including a Multiple Linear Regression and a Linear Mixed-Effects Model. The results consistently show an heterogeneity in baseline waste per capita generation and that higher levels of income are associated with larger average individual outputs of waste. While Bayesian models showed a tendency for Pay-As-You-Throw (PAYT) schemes to decrease waste, the 95% credible intervals often included zero, suggesting no statistically significant effect. In contrast, estimating the effect of the adoption of a PAYT scheme using both frequentist approaches produced statistically significant negative effect. Overall, while regional differences and income effects are evident, the impact of PAYT schemes remains uncertain across different modeling approaches and a significant portion of waste per capita variability remains unexplained.

---

## Repository Structure

`Regional Disparities in Waste Management.rmd`: This is the core RMarkdown file for the project. It contains:
- The complete code used for data cleaning and exploratory data analysis.
- The development and implementation of the statistical models.
- The code used to generate all the figures and tables presented in the final project report.


`models/`: This directory stores all text files related to the **JAGS** modeling implemented in this project:

- `fixed_effect_waste_pc.txt`: This `.txt` file contains the **JAGS** model used to implement the **Fixed Effect Bayesian Model**.
- `random_effect_waste_pc.txt`: This `.txt` file contains the **JAGS** model used to implement the **Random Effect Bayesian Model** (Hierarchical Model).

These files are called in the RMarkdown script to perform the model fitting.

---

## Project Report

A detailed explanation of the project's methodology, experiments, results, and conclusions can be found in the [Final Project Report](<Regional Disparities in Waste Management>).