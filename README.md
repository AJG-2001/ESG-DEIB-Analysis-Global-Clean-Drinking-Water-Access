ESG & DEIB Analysis – Global Clean Drinking Water Access

📌 Project Overview

This project investigates disparities in global clean drinking water access, with a focus on rural vs. urban populations. By applying regression, classification, and clustering techniques, the analysis identifies patterns, forecasts rural water access, and highlights regions most at risk of inequitable water distribution.

The project ties directly to Environmental, Social, and Governance (ESG) goals and integrates Diversity, Equity, Inclusion, and Belonging (DEIB) considerations by evaluating fairness, bias, and inclusivity in data modeling
.

🔎 Research Objective

ESG Issue: Clean and safe drinking water is a human right, yet ~2 billion people rely on contaminated sources (WHO, 2023). Rural populations face disproportionate risks due to lack of infrastructure, finance, and governance.

Goal: Use data-driven modeling to analyze water access disparities and generate actionable insights for achieving UN SDG 6 – Clean Water & Sanitation.

Intersection with DEIB: Ensure models account for geographic, social, and economic inequalities and minimize bias in predictions
.

🛠️ Data & Methods
Data Sources

WHO, UN, and World Bank datasets on water access, demographics, and governance.

Key variables: rural basic access, unimproved access, population, GDP per capita, region, and governance indicators
.

Methodology

Data Preprocessing

Managed missing values via imputation.

Encoded categorical features (e.g., region, governance type).

Scaled numeric variables for comparability.

Exploratory Data Analysis (EDA)

Boxplots, scatterplots, correlation analysis, and time-series trends.

Regression Models (Forecasting Rural Access)

Linear Regression, Decision Trees, Random Forest, KNN.

Best Model: Random Forest Regressor (R² = 0.97, MAE = 0.02).

Classification Models (High vs Low Access)

Logistic Regression, Decision Tree, Random Forest, KNN.

Best Model: Random Forest Classifier (highest F1-score).

Clustering Models (Country Grouping)

K-Means (best silhouette score), Hierarchical, DBSCAN.

Identified 3 clusters: High Access (>90%), Moderate Access (60–90%), Low Access (<60%)
.

📊 Key Findings

Regression Forecasts: Rural water access predicted to improve with urbanization and infrastructure investment. Africa remains the most vulnerable region.

Classification Results: Random Forest best at distinguishing low-access nations; Logistic Regression struggled with false negatives.

Clustering Analysis:

Cluster 1: Developed nations with >90% rural water access.

Cluster 2: Emerging economies with 60–90% access.

Cluster 3: Severe water crises in sub-Saharan Africa and parts of South Asia.

Practical Use: Predictive models can guide infrastructure planning, resource allocation, and targeted interventions
.

🌍 ESG & DEIB Implications
Environmental (E)

Climate-driven scarcity increases urgency for sustainable water infrastructure.

Predictive analytics can support climate resilience strategies.

Social (S)

Access gaps affect public health, poverty, and gender equity (women disproportionately bear water collection burdens).

Targeted policies can improve inclusivity in resource allocation.

Governance (G)

Data-driven policymaking improves accountability and progress tracking on SDG 6.

Supports international cooperation for underprivileged regions
.

DEIB Considerations

Bias Risks: Underrepresentation of African & South American data skewed model predictions.

Mitigation: Grouping by continent, fairness checks by region, and ethical visualization ensured inclusivity.

Future Improvements: Apply fairness-aware ML (e.g., re-weighting underrepresented data, socioeconomic integration)
.

🗂️ Deliverables

Assignment_A1_Individual_Report.pdf – Written report (ESG framing, DEIB ethics, social implications).

Assignment_A1_Individual_Project.ipynb – Python notebook (EDA, regression, classification, clustering).

clean_drinking_water.csv – Processed dataset.

JMP_2023_WLD.xlsx – Supplementary data from WHO/UN.

README.md – Project overview (this file).

🚀 Key Takeaways

Random Forest models are best suited for predicting rural water access and classifying high- vs low-access countries.

Predictive analytics can guide governments, NGOs, and corporations toward ESG-aligned water stewardship programs.

Fairness considerations are essential: models must account for data imbalance and regional representation.

Data science can directly support SDG 6 (Clean Water & Sanitation), SDG 10 (Reduced Inequalities), and SDG 13 (Climate Action).
