# Healthcare-Insights-Dashboard
<img width="604" alt="Healthcare Insights Dashboard" src="https://github.com/user-attachments/assets/054c0039-abe8-48d6-8484-21f18eb8f85f" />

## Data Overview
The dataset provides a comprehensive view of healthcare access and utilization among sample size of about 6000. It includes demographic, socioeconomic, and healthcare-related information, enabling a detailed analysis of healthcare trends and gaps.
## Objective of the Dataset
* Assess healthcare access and gaps.
* Analyze the relationship between demographics, income, and healthcare utilization.
* Highlight areas for healthcare improvement,
## Steps
### Data Cleaning[(Here)](https://colab.research.google.com/drive/1KfCUp94_BdYISbvGaFxzbN33jnEaQGTp?usp=sharing)
1. Remove duplicates.
2. Fill missing values in the 'If yes, ' column with 'Unknown' in the following columns;Routine HealthCheck, Cancer Screening and Health Insurance.
3. Insurance type was based on Insurance Regulation Authority(IRA)
4. Group insurance types with less than 50 as "Others"
5. Group no. of children into small,medium and large families determined by no. of children.
### Visualization
Achieved with PowerBi.The Dashboard visualizes demographic distribution, healthcare insurance status, check-up frequencies, and income levels.

## Findings
* Gender Distribution.The population is evenly distributed between male and female respondents, with negligible "unknown" cases.
* Age Groups: Most respondents are aged 18–30 (34.7%), followed by 31–40 (28.3%).
* Monthly Household Income: Nearly 30% earn less than 10,000 per month, with higher income groups progressively decreasing.
* Insurance Coverage:A majority are covered by NHIF (46.1%), while 42.2% have no insurance.
* Routine Check-ups and Cancer Screening:A significant proportion of respondents do not undergo regular check-ups or screenings.Those who do tend to follow longer intervals between visits.
* Small families (1–3 children) dominate (53.3%), while 23.7% have 7+ children.
## Recommendations
1. Expand Awareness Campaigns:Educate individuals about the importance of health insurance, targeting underserved populations.
2. Promote partnerships between public and private sectors to provide affordable premiums.
3. Community Health Programs:Organize regular health camps in underserved areas to provide free or subsidized check-ups.
4. Improved Accessibility in Rural Areas:Increase the number of healthcare centers in underserved regions.


