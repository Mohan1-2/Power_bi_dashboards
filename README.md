# Power_bi_dashboards
![image](https://github.com/user-attachments/assets/9deb6b26-0c54-40cb-bf72-2b7bf4f48276)

The primary objective of analyzing the CFSAN Adverse Event Reporting System (CAERS) dataset is to gain a comprehensive understanding of adverse events associated with foods, dietary supplements, and cosmetics as reported to the FDA.
### **Background**

The CAERS database is a critical tool for the FDA, containing adverse event and product complaint reports related to foods, dietary supplements, and cosmetics. This dataset, covering the period from 2004 to the second quarter of 2017, includes detailed records of various products and associated adverse events. Each record is meticulously coded using the Medical Dictionary for Regulatory Activities (MedDRA) terminology, ensuring standardized reporting across different products. The data captures elements like report numbers, product roles, brand names, industry codes, patient demographics, adverse outcomes, and coded symptoms.
### **Objective**

The primary objective of analyzing the CFSAN Adverse Event Reporting System (CAERS) dataset is to gain a comprehensive understanding of adverse events associated with foods, dietary supplements, and cosmetics as reported to the FDA. This analysis aims to identify patterns and trends in these events, including the distribution across different product categories, the demographic characteristics of those affected, and the types and severities of reported symptoms and outcomes. By exploring these aspects, the analysis seeks to contribute valuable insights for enhancing product safety surveillance, informing regulatory policies, and ultimately improving public health outcomes by identifying potential risks and areas for intervention in the industries of food, dietary supplements, and cosmetics.

## Data Source

The analysis is based on the CAERS_ASCII_2004_2017Q2.csv file, which contains the following key fields:

RA_Report: Unique identifier for each adverse event report.

RA_CAERS Created Date: Date of report entry into the CAERS database.

AEC_Event Start Date: Date the adverse event began.

PRI_Product Role: Role of the product (suspect or concomitant).

PRI_Reported Brand/Product Name: Product name associated with the event.

PRI_FDA Industry Code & Name: Industry categorization (e.g., 'Bakery Prod/Dough/Mix/Icing', 'Ice Cream Prod').

CI_Age at Adverse Event: Age of the affected individual.

CI_Age Unit: Age measurement unit (years, months).

CI_Gender: Gender of the affected individual.

AEC_One Row Outcomes: Event outcomes (hospitalization, ER visit, etc.).

SYM_One Row Coded Symptoms: Coded symptoms related to the event.

## Part I : Data Cleaning, Modeling, and DAX in Power BI
Data Importing and Preprocessing
The dataset is imported into Power BI for initial exploration and examination. Data quality issues, including missing values and incorrect data types, are addressed.

Data Analysis
Product Role Categorization: Categorize products based on their role (suspect or concomitant) to analyze distribution across roles.

Industry-Based Analysis: Group data by FDA industry names and examine the distribution of reports within various industries.

Demographic and Gender Analysis: Analyze the demographic spread of adverse events based on age and gender.

Symptom Frequency and Correlation: Investigate common symptoms and their correlations with patient age, using DAX for advanced calculations.

Outcome and Industry Relationships: Analyze the relationship between industry types and adverse event outcomes, categorizing them by severity.

Time Series Analysis: Conduct a time-based trend analysis of report submissions.

Advanced Modeling with DAX: Develop predictive models for adverse event risks based on age, product type, and symptom severity

## Part 2: Dashboard Building
# Adverse Event Reporting Dashboard
The dashboard provides key metrics on report frequency, common symptoms, and product types, with interactive filters for detailed analysis by industry, product role, age group, and gender.

![image](https://github.com/user-attachments/assets/604880ad-17d1-44e1-8c7f-e347f7986c49)

# Demographic Analysis
The dashboard visualizes reporting trends over time and allows users to explore data by age and gender to identify demographic patterns in Adverse Event

![image](https://github.com/user-attachments/assets/fb2c15f4-a964-46d5-8939-dc5db8372fef)

#  Industry and outcome analysis
Interactive visuals illustrate the correlation between industries and reported outcomes, providing insights into potential high-risk categories and trends

![image](https://github.com/user-attachments/assets/db6df1f8-d460-449a-9ec3-f89103019671)



## Link for Dashboard
Explore the dashboard at this link below to dive deeper into the data and uncover more opportunities for enhancing manufacturing efficiency.
https://drive.google.com/file/d/1Vp3hX67uPlMUlHmBYVXQXc_jOcFDulNG/view?usp=sharing

# Data Storytelling and Insights
The dashboard integrates storytelling techniques to summarize key insights derived from the data, helping users quickly identify the most important findings. Key Features Comprehensive Data Analysis: Detailed examination of the adverse event data using Power BI, including DAX-driven insights and predictive modeling. Interactive Dashboard: User-friendly, accessible Power BI dashboard for exploring trends, correlations, and demographics.

# Conclusion
This analysis of adverse event data for the food and cosmetics industries provides essential insights into safety issues and trends. The results of this project are expected to inform future product safety regulations and support the FDA’s goal of improving public health by mitigating potential risks associated with food and cosmetic products.
