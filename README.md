# DATA 205 Capstone Project  
## Exploring Income Inequality Across Maryland Counties  
### The Impact of Education and Internet Access

**Farah Makkawi**

---

## Project Overview

This project analyzes income differences across Maryland counties and examines how education and internet access influence economic outcomes. The analysis originally focused on Montgomery County and Prince George’s County but was expanded to include all 24 Maryland counties to provide a broader and more statistically meaningful analysis.

The goal of the project is to identify relationships between median household income, education levels, and internet access across Maryland counties and determine whether these relationships are statistically significant.

---

## Research Questions

- How does education level relate to median household income across Maryland counties?
- How does internet access relate to median household income?
- Are income differences between Maryland county groups statistically significant?
- Can education and internet access predict income levels across counties?

---

## Data Sources

- U.S. Census Bureau (data.census.gov)
- Maryland Open Data

The dataset includes:
- Median household income
- Bachelor’s degree percentage
- Internet access percentage
- Population
- Maryland county group classifications

---

## Methods Used

This project includes both exploratory data analysis (EDA) and statistical analysis techniques:

### Exploratory Data Analysis (EDA)
- Bar charts
- Scatterplots
- County comparisons
- Correlation heatmaps

### Statistical Analysis
- Correlation analysis
- Simple linear regression
- Multiple linear regression
- Polynomial regression
- ANOVA testing

---

## Key Findings

- Counties with higher education levels tend to have higher median household income.
- Internet access showed the strongest relationship with income.
- Multiple regression analysis explained approximately 82% of the variation in county income levels.
- ANOVA testing confirmed statistically significant income differences between Maryland county groups.
- Polynomial regression models suggested that the relationships are mostly linear.

---

## Statistical Results

| Analysis | Result |
|---|---|
| Education vs Income Regression | Significant positive relationship |
| Internet Access vs Income Regression | Significant positive relationship |
| Multiple Regression R² | ~0.82 |
| ANOVA p-value | ~0.003 |
| Correlation: Income & Internet Access | ~0.87 |
| Correlation: Income & Education | ~0.78 |

---

## Project Structure

```text
Data-205/
│
├── data/
│   ├── income.csv
│   ├── education.csv
│   ├── internet_access.csv
│   └── population.csv
│
├── notebooks/
│   └── DATA205_Capstone_FarahMakkawi_Final_StatisticalAnalysis.ipynb
│
└── README.md









