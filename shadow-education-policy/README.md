# 🎓 Examining the Use of Shadow Education under the Double Reduction Policy


## 📘 Introduction

Shadow education—commonly referred to as private tutoring—has expanded rapidly across East Asia, especially in China, where academic pressure and competition for elite universities are intense. In 2021, the Chinese government implemented the **Double Reduction policy** to reduce students' academic burdens and regulate the booming private tutoring industry. While official reports suggest a decline in tutoring institutions, **empirical research on actual participation trends remains limited**.  
This study addresses that gap using national panel data from the **China Family Panel Studies (CFPS)** to analyze how students' engagement in shadow education changed after the policy and how these changes vary by family socioeconomic status (SES) and geographic region.

---

## 🧠 Theoretical Framework

This research draws on two key theoretical perspectives:

- **Human Capital Theory (Becker, 1964)**  
  Families treat education as an investment to improve their children’s future labor market outcomes. Higher-SES families are more likely to invest in tutoring services to enhance academic performance and long-term success.

- **Social Reproduction Theory (Bourdieu, 1977)**  
  Educational inequality is reproduced across generations. Shadow education is viewed as a form of **cultural capital**, giving high-SES families an advantage in maintaining or improving their social status through unequal access to private educational resources.

These frameworks inform the analysis of SES-based disparities in tutoring participation before and after the Double Reduction policy and provide insight into the persistent demand for tutoring despite regulatory efforts.

---

## 🧪 Data & Methodology

- **Data Source**: China Family Panel Studies (CFPS), 2020 & 2022 waves  
- **Sample**: 2,016 students (Grades 1–9) across 28 provinces  
- **Analysis**: Descriptive statistics, chi-square tests, correlation analysis, logistic regression  
- **Variables**: Shadow education types (subject-based, interest-based, competition, one-on-one), family SES, school location, academic performance, parental expectations, etc.

---

## 💻 Coding Strategy

- Given that Stata operates on a single active dataset at a time, the standard procedure involves separately cleaning data from multiple sources and subsequently merging them into a consolidated analytical dataset using the merge command, thereby facilitating comprehensive and consistent statistical analysis
- The 2020 wave serves as the baseline, with key variables extracted on children’s demographic characteristics, academic performance, and engagement in shadow education. To construct a longitudinal dataset, child-, person-, and family-level questionnaires were cleaned separately and subsequently merged using Stata’s **merge** command, following the standard practice of consolidating multiple data sources into a single analytical file for unified statistical analysis. Variable codings were harmonized to ensure comparability across waves.

---

## 🔍 Key Findings

- Subject-based tutoring **increased** slightly after the policy, contrary to expectations  
- **Interest-based tutoring declined**, likely due to rising exam pressure  
- Participation rates remained **highest among high-SES families**  
- Regional trends diverged: tutoring **declined in the East** but **rose in Central China**  
- SES continued to be a significant predictor of tutoring, although its effect slightly weakened in 2022

---

## ⚠️ Limitations

- Causal inference limited due to observational study design  
- Only short-term effects observed (2020–2022)  
- Regional implementation strength not directly measured

---

## 📌 Policy Implications

To truly reduce educational inequality, policymakers must look beyond regulation and address root causes of academic pressure. Recommendations include:

- Promoting **diverse, holistic student evaluation systems**
- Expanding access to **high-quality public education**
- Supporting **lower-SES families** with free or subsidized academic support services

---
