# Global Country Indicators Analysis – R Statistical Modeling Project

## Navigation
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Research Questions](#research-questions)
- [Methods Used](#methods-used)
- [Tools and Technologies](#tools-and-technologies)
- [Key Findings](#key-findings)

---

## Project Overview
This project analyzes global economic, social, health, education, environmental, and demographic indicators using statistical methods. The analysis focuses on identifying relationships between countries and comparing Turkey with global patterns using applied statistical techniques.

---

## Dataset
The dataset contains approximately 195 countries and 35 variables for the year 2023.

The dataset includes indicators such as:
- GDP
- Life Expectancy
- CO2 Emissions
- CPI
- Education Enrollment Rates
- Health Expenditure
- Agricultural Land Percentage
- Infant Mortality
- Population Metrics

The data was cleaned and prepared using R. Variable inconsistencies such as numeric formatting differences were corrected during preprocessing.

---

## Research Questions
The project investigates the following research questions:

- Are average agricultural lands in European countries equal to the EU target of 37 percent?
- Is the average gasoline price different between European and North American countries?
- Does having a higher CPI also mean a higher CPI increase?
- How can Turkey’s life expectancy be estimated based on demographic indicators?
- Do countries from different continents have different average forested areas?
- Does physician density significantly affect infant mortality outcomes?

---

## Methods Used
The project applies multiple statistical and modeling techniques, including:

### Data Preparation
- Data Cleaning using R
- Data Type Standardization
- Missing Value Handling

### Hypothesis Testing
- One Sample t-test  
- Two Sample t-test  
- One-Way ANOVA  
- Two-Proportion Z-Test  
- Fisher Exact Test  

### Regression Modeling
- Simple Linear Regression  
- Multiple Linear Regression  

All model assumptions such as normality, homoscedasticity, independence, and multicollinearity were checked before applying statistical tests.

---

## Tools and Technologies
- R (Data Cleaning, Statistical Testing, Modeling)
- Tableau (Data Visualization)
- Kaggle (Dataset Source)

---

## Key Findings
- The average agricultural land percentage of European countries is aligned with the EU target.
- European countries have higher average forested areas compared to African and Asian countries.
- Africa and Asia do not show statistically significant differences in forested area averages.
- Gasoline prices are significantly higher in Europe compared to North America.
- Countries with higher physician density are significantly more likely to have low infant mortality rates.
- Turkey shows strong agricultural land indicators but mixed results in environmental comparisons.

---
