Heart Health Analysis

Problem Statement: Analyze patient clinical data to identify key factors associated with heart disease risk and provide data-driven insights to support early diagnosis and preventive healthcare strategies.


Steps:
- Explored relationship between medical features and heart disease target.
- Correlation analysis and predictive insights.
- Tools Used: Python, EDA, Statistical Analysis

Key Insights & conclusion:
- Female have higher resting blood pressure.
- There is weak positive relationship between age and cholesterol.
- Late 50's patients showing all kinds of chest pain variants.
- Heart disease cases are more concentrated in middle-aged individuals (50–60), suggesting risk rises significantly after 45. Cholesterol alone does not clearly separate heart disease vs non-disease groups — indicating weak standalone predictive power.
- Certain clinical indicators (such as cholesterol levels, resting blood pressure, and maximum heart rate) display meaningful associations with the target variable.
- Patients with exercise-induced angina are more likely to exhibit heart disease.

Challenges Faced :
 - Medical variables had different scales and distributions, requiring careful interpretation.
 - Correlations between features were moderate, making prediction dependent on combined indicators rather than individual metrics.
 - Presence of outliers in clinical measurements could skew summary statistics.
 - Translating statistical relationships into clinically meaningful insights required domain-aware interpretation.

Recommendations :
  Preventive Healthcare
 - Prioritize screening for older patients and those showing exercise-induced angina.
 - Monitor cholesterol and blood pressure trends proactively.
 - Encourage lifestyle interventions for high-risk segments.

Detailed analysis in the code attached in folder.
