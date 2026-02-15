# cancer-severity 
Overview
This project analyzes cancer patient data in India from 2015 to 2024 to identify key lifestyle, environmental, and genetic factors influencing cancer severity and to study the increasing trend of cancer cases. Statistical methods are used to support evidence-based public health insights.

Objectives
Identify major risk factors affecting cancer severity
Analyze yearly trends in cancer patient counts
Quantify the impact of lifestyle, environmental, and genetic factors
Provide insights for prevention and early detection strategies

Data Used
global_cancer_patients_2015_2024.csv (India-specific subset)
increasing_cancer_patients_rates.csv (Year-wise patient counts)

Key Variables:
Age, Gender, Genetic Risk, Smoking, Alcohol Use, Air Pollution, Obesity Level, Cancer Stage, Survival Years, Target Severity Score

Methodology
EDA: Data cleaning, descriptive statistics, visual exploration
Correlation: Pearson & Spearman to assess relationships
ANOVA: Tested survival differences across cancer stages
Regression: Multiple linear regression to identify strongest predictors
Trend Analysis: Yearly cancer incidence trends (2015–2024)

Key Findings
Smoking and genetic risk are the strongest contributors to cancer severity
Alcohol use and air pollution show moderate influence
Obesity has a weaker but significant effect
Cancer cases in India show a steady increasing trend
Regression model explains ~80% of severity variation

Conclusion
Cancer severity in India is strongly influenced by modifiable lifestyle factors along with genetic predisposition. The rising incidence of cancer highlights the need for early screening, prevention policies, and public awareness programs.

Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels

References

ICMR, WHO, Global Cancer Observatory (IARC), peer-reviewed cancer epidemiology studies
