# GWONWOO (JUSTIN) CHA - Portfolio

## About Me
I leverage data-driven insights to optimize business performance and support strategic decision-making. My expertise spans predictive modeling, dashboard design, and business intelligence, with a proven ability to translate complex data into actionable outcomes.

## Table of Contents
- [About Me](#about-me)
- [Education](#education)
- [Portfolio Projects](#portfolio-projects)
  - [PowerBI]
    - [Market Expansion Decision Intelligence Dashboard – Korean Supermarket Feasibility Analysis (50 U.S. States)](#market-expansion-decision-intelligence-dashboard--korean-supermarket-feasibility-analysis-50-us-states)**
  - [Tableau]
    - [Tableau healthcare dashboard](#tableau-healthcare-dashboard)
  - [Python]
    - [Xente E-commerce Loan Default Prediction](#xente-e-commerce-loan-default-prediction)
  - [R]
    - [SVM model using R to predict energy consumption on extra hot summer](#svm-model-using-r-to-predict-energy-consumption-on-extra-hot-summer)

## Education

### Syracuse University, School of Information Studies
**Degree:** B.S. in Applied Data Analytics  
**Expected Graduation:** May 2025  
**Cumulative GPA:** 3.8/4.0  
**Honors/Awards:** Dean’s List (Fall 2022, Spring 2023, Fall 2023, Spring 2024, Fall 2024 & Spring 2025)  

## Work Experience

### Administrative Manager | Jeuonnam US
**Los Angeles, CA | Jun 2025 – Present**
- Managed nationwide market analysis across 50 U.S. states, analyzing 2.5K+ rows with Microsoft SQL Server to rank for permanent retail store expansion, informing future site selection strategy.
- Designed a Power BI dashboard to score all 50 U.S. states for retail market feasibility using Z-score and CDF percentile scoring (0–100 index), where Maryland ranked among the top-performing states with a score of 80/100, adopted by Jeonnam HQ executives and prompting on-site market validation.
- Analyzed 1K+ rows from GA4 and Meta Business Suite using BigQuery to evaluate Maryland event performance by designing a KPI dashboard in Looker Studio based on funnel and ROI analysis.
- Optimized external stakeholder management data by centralizing contacts in an Excel-based database with enforced data standards, including dropdown selection and auto-validation, cutting data entry and lookup time by 50%.

### Business Intelligence Analyst | Syracuse University
**Syracuse, NY | Jan 2025 – May 2025**
- Designed interactive Tableau dashboards to surface trend signals and measure program effectiveness by tracking retention shifts, major mobility, peer mentor engagement, resource awareness, and perceived value of academic training.
- Interpreted longitudinal trend patterns across 1.2K+ student records from 20+ institutional datasets, synthesizing demographic shifts, academic pathway movement, retention variance, and competence growth indicators.
- Presented a trend insights report to senior administrators, shifting mentorship strategy from broad support to trend-targeted guidance for 500+ high-interest mobility students, showing transition trends toward tech-oriented academic pathways.

### Teaching Assistant for Networks and Clouds at Syracuse University, Syracuse, NY
**Duration:** Jan 2024 – Apr 2024  
- Volunteered as a Teaching Assistant for the Networks and Clouds course, leading 4-hour weekly lab sessions for 73 students.
- Collaborated with 2 graduate Teaching Assistants to build an Excel-based academic performance tracking system, documented findings for the professor, and guided weekly 1:1 mentoring sessions for students.
- Mentored 24 low-performing students through weekly 1:1 mentoring sessions, achieving a 100% course pass rate.

### Business Development Intern at Day 1 Company, Seoul, KR
**Duration:** June 2022 – Aug 2022  
- Analyzed historical sales data, 50+ digital education products, and positioning of 10+ competitors to uncover customer preferences and guide course topic selection, informing the company’s first U.S. market entry strategy in a niche market.
- Collaborated with the marketing team by analyzing Shopify sales and user data, sharing insights on customer behavior to
improve the sales conversion rate.

## Relevant Projects

### PowerBI
### Market Expansion Decision Intelligence Dashboard – Korean Supermarket Feasibility Analysis (50 U.S. States)
**Dashboard**
https://app.powerbi.com/groups/me/reports/110a9691-05d9-40e6-ad65-b7955e6cf56c/a9173a68289c95dfb74b?experience=power-bi
[1Korean Market Feaibility 
(Final).pdf](https://github.com/user-attachments/files/22901871/Korean.Market.Feaibility.Final.pdf)

**Goal:**

This decision intelligence asset was developed to operationalize market feasibility evaluation for Korean supermarket expansion across the United States. Instead of functioning as a standard visualization, the dashboard is positioned as an executive-facing briefing tool designed to prioritize investment regions using a weighted scoring architecture rooted in market capacity and cultural affinity metrics.


**Description:**

To identify the most viable U.S. state for a Korean retail market entry, I initiated a nationwide market analysis across 50 states by aggregating and processing 2.5K+ demographic, income, cultural affinity, and retail density data points using Microsoft SQL Server. Rather than relying on single metrics like population or K-community size, I engineered a composite Market Feasibility Index (MFI), applying Z-score normalization and CDF percentile scoring to fairly compare states regardless of outliers in market size. I then visualized this scoring model in a Power BI dashboard that ranked each state on a standardized 0–100 feasibility scale. The analysis surfaced Maryland as a high-potential expansion candidate with an MFI score of 80/100, which led Jeonnam HQ executives to adopt the dashboard as a decision brief and approve an on-site market validation visit to verify retail expansion potential firsthand.

**Dataset**

| Dataset | Records | Strategic Interpretation for Decision Intelligence |
|--------|--------|------------------------------------------------------|
| Korean Restaurants | 50+ | Cultural presence benchmark (offline adoption indicator) |
| Korean Companies | 900+ | Ethnic commercial infrastructure signal |
| Asian Market | 50+ | Retail scalability and distribution readiness |
| Total Population | 50+ | Macro market volume baseline |
| Korean Population & Asian Population | 100+ | Demand-side demographic feasibility |
| Median Household Income | 50+ | Consumer purchase power index |
| Google Trend – K-Culture Keywords | 1200+ | Digital cultural affinity and search intent intensity |

**Weighted Scoring Logic**

Final Feasibility Score = 0.15 * [TotalPop_Score] + 0.15 * [AsianPop_Score] + 0.20 * [AsianMarketDensity_Score] + 
0.25 * [MedianIncome_Score] + 0.25 * [KCulturePopularity_Score]

Cultural Affinity Index:
0.4 * Z(Korean Restaurants) + 0.3* Z(Korean Businesses) + 0.3* Z(Google Trend Interest)

### Tableau
### Tableau Healthcare Dashboard 
**Dashboard**
![Tableau Slide 1](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau1.png)
![Tableau Slide 2](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau2.png))
![Tableau Slide 3](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau3.png)
![Tableau Slide 4](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau4.png)
![Tableau Slide 5](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau5.png)
![Tableau Slide 6](https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/tableau6.png)

**Goal:** 
Provide a comprehensive visual analysis of the U.S. healthcare system to offer actionable insights to stakeholders, helping them to improve healthcare outcomes and inform policy decisions across different states in the U.S.

**Description:** 
Healthcare Performance Dashboard:
This dashboard provides a critical overview of state-wise healthcare performance in the U.S., particularly focusing on the impact of COVID-19. Key insights include ICU bed occupancy, avoidable deaths, maternal mortality rates, and COVID-19 cases. It serves as a benchmark for policymakers and healthcare providers to assess and plan future healthcare initiatives.

New Enrollment Dashboard:
Analyzes Original Medicare-Medicaid Enrollment (MME) data by program type and geographical distribution. Highlights include insights on full-benefit and partial-benefit programs, enrollment trends from 2013-2021, and a regional analysis of MME distribution.

Hospice Analytics Dashboard:
Presents national hospice care metrics, focusing on discharge rates, care gaps, hospitalization rates, and patient experiences. It provides a state-by-state and national perspective on hospice care quality and ownership.

Healthcare Spending Dashboard:
Offers a detailed visual analysis of U.S. healthcare spending per capita, highlighting state-level variations and historical spending trends. This dashboard allows for the exploration of how spending patterns have evolved over time.

Total Enrollment Dashboard:
Focuses on Total Medicare-Medicaid Enrollment (MME) data, categorized by program type and age demographics. It delivers insights into program accessibility and cumulative enrollment trends.

**Technology:** 
Tableau

**Detail**
(https://github.com/GwonwooC/Navigating-US-Healthcare/blob/main/README.md)

### Python

#### Xente E-commerce Loan Default Prediction
**Code:**  
[Repository Link](https://github.com/GwonwooC/Credit-Scoring-Challnege)

**Goal:**  
Predict the likelihood of loan default for e-commerce customers using historical transaction data to inform risk assessment and improve loan approval processes.

**Description:**  
In this project, I utilized customer transaction data from Xente, an e-commerce platform, to predict loan default probability. Key steps included data cleaning, feature engineering, and implementing machine learning models to assess loan risk. Various models were evaluated, including Logistic Regression, Random Forest, and Gradient Boosting, to identify significant features affecting loan repayment. The project involved balancing data through resampling to address class imbalance, ensuring robust predictive accuracy.

**Skills:**
Data Preprocessing, Feature Engineering, Logistic Regression, Random Forest, Gradient Boosting, Model Evaluation

**Technology:**  
Python, Pandas, Scikit-Learn, imbalanced-learn

**Results:**  
The best model achieved an accuracy of 86% in predicting loan default, offering significant insights into loan approval risk management.

**Detail Report:**  
[Full Report](https://github.com/GwonwooC/Credit-Scoring-Challnege#readme)

### SVM model using R to predict energy consumption in an extra hot summer
**Code:** 
(https://github.com/GwonwooC/eSC/blob/main/project_preprocessing.R)
(https://github.com/GwonwooC/eSC/blob/main/project_modeling.R)

**Goal:** 
Predict energy consumption during exceptionally hot periods(time) using historical data to mitigate the risks of blackouts associated with increased electricity demand

**Description:** 
The project focused on predicting energy consumption during exceptionally hot periods to mitigate the risk of blackouts due to increased electricity demand. The datasets included static house data with details about residential properties and their insulation, sample weather data providing weather conditions for the house locations, and energy usage data detailing electricity consumption for various household items, particularly HVAC usage. The project involved loading and preprocessing the data, integrating the datasets, performing exploratory data analysis (EDA), analyzing the correlation between various factors affecting energy usage, and implementing the Support Vector Regression (SVR) model for prediction.

**Skills:** 
data cleaning, data analysis, SVR, linear regression, decision tree, data visualization.

**Technology:** 
tidyverse, arrow, caret, e1071, rpart, dplyr, ggplot

**Results:** 
Using R functions the analysis revealed that after 5:30 PM the energy usage increases steeply and it extends until 11 PM

**Detail Report:** 
(https://github.com/GwonwooC/eSC/tree/main#readme)

---

&copy; 2024 GWONWOO (JUSTIN) CHA. All Rights Reserved.
