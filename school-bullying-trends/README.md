# School Bullying Trends in the Post-Pandemic Era  
**A Cross-National Comparative Study Using PISA 2018 and PISA 2022**

## 🧭 Project Overview
This research project investigates cross-national trends in school bullying in the aftermath of the COVID-19 pandemic. Drawing on large-scale, representative data from the Programme for International Student Assessment (PISA) in 2018 and 2022, the study examines changes in the prevalence of bullying victimization among adolescents across 80 countries. It further explores the associations between bullying victimization and science-mathematics achievement, with particular attention to gender-based differences.


## 📂 Data and Scope
### Data Sources:  
  - [PISA 2018 Student Questionnaire Data (OECD)](https://www.oecd.org/pisa/data/2018database/)
  - [PISA 2022 Student Questionnaire Data (OECD)](https://www.oecd.org/pisa/data/2022database/)
    
### Sample: Approximately 600,000 15-year-old students per cycle across 80 participating countries or economies.
  
### Key Variables Description
**🎯 Dependent Variable**
- `BULLIED` / `BEINGBULLIED`  
  - **Description**: Self-reported indicator of whether the student experiences bullying victimization.  
  - **Type**: Binary (e.g., 0 = Not Bullied, 1 = Bullied)

**📈 Independent Variables** 
- `PV1MATH` – `PV5MATH`  
  - **Description**: Five plausible values representing mathematics achievement.  
  - **Use**: For imputation or averaged as a predictor of academic performance.

- `PV1SCIE` – `PV5SCIE`  
  - **Description**: Five plausible values representing science achievement.  
  - **Use**: Same as above, representing performance in science.

- `Gender`  
  - **Description**: Re-coded binary gender variable.  
  - **Type**: Binary (e.g., 0 = Male, 1 = Female)

## 🔬 Methodological Approach
Data analysis was conducted using IBM SPSS 24 and Stata MP 18. The following methods were employed:
- **Descriptive statistics** to examine the distribution and trends in bullying victimization.
- **Independent sample t-tests** to compare gender differences in victimization and academic achievement.
- **Ordinary Least Squares (OLS) regression** to assess the relationship between bullying victimization and science-mathematics performance, controlling for gender.

## 🎓 Key Findings
1. **Decline in bullying post-pandemic**: A general reduction in bullying victimization was observed across most countries in 2022 compared to 2018.
2. **Negative academic impact**: Victims of bullying reported significantly lower science-mathematics achievement, highlighting the cognitive and emotional toll of peer victimization.
3. **Gender disparities**: Males were more likely to report bullying victimization and also showed higher mean achievement scores in STEM domains than females.

