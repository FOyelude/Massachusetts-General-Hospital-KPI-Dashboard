# Massachusetts-General-Hospital-KPI-Dashboard

## Project Description

For the Maven Hospital Challenge, I acted as an Analytics Consultant for Massachusetts General Hospital (MGH). The task was to build a high-level KPI report using a subset of patient records. The purpose of the report was to provide the executive team with crucial insights into the hospital's recent performance.

### GOALS
- Analyze patient admission and readmission trends over time.
- Determine the average length of hospital stays.
- Calculate the average cost per visit.
- Assess the number of procedures covered by insurance.

### Business Needs
The executive team required a comprehensive dashboard to gain visibility into the hospital's performance and answer key questions about patient admissions, hospital stay durations, costs, and insurance coverage. This would enable informed decision-making and strategic planning to enhance operational efficiency and patient care quality.

### Process to Discover and Present Meaningful Insights
1. **Data Loading and Transformation:**
   - Loaded patient records into Power BI.
   - Transformed the data to ensure accuracy and consistency.
  
   **Data Structure Overview**
   

3. **Creating the Dashboard:**
   - Built the dashboard in Power BI to visualize KPIs.
   - Developed measures and calculated columns to analyze patient admissions, readmissions, average stay durations, and costs per visit.
   - Filtered and cleaned data to ensure the inclusion of relevant information and the removal of any duplicates or errors.

### KEY INSIGHTS
- **How many patients have been admitted or readmitted over time?**
  - There were a total of 28,000 admissions to the hospital.
  - The readmission rate was 44.61%, a critical indicator of healthcare quality and patient management.
  - Seniors exhibited the highest readmission rate at 50%, suggesting that older patients require more intensive follow-up care.
  - Among racial groups, the Native population had the highest readmission rate, indicating potential disparities in healthcare access or quality that need to be addressed.

- **How long are patients staying in the hospital, on average?**
  - The average length of hospital stays was 7.3 hours.
  - In 2014, the average stay length peaked at 38.01 hours, driven primarily by a significant number of admissions to the Intensive Care Unit (ICU). This suggests that 2014 was a year with particularly severe cases requiring prolonged care.
  - Since 2020, there has been a steady decline in the average length of hospital stays, which could be attributed to improvements in healthcare efficiency and patient management.

- **Which procedures have the highest death rates?**
  - Certain procedures, such as "Computed tomography of chest and abdomen," had a 100% mortality rate, highlighting the severe condition of patients undergoing these procedures.
  - This data underscores the critical need for continued research and potential improvements in care for patients requiring these high-risk procedures.

- **How much is the average cost per visit?**
  - The average cost per hospital visit was $3.64k, with the highest costs recorded in 2012.
  - The increasing trend in costs through 2022, where the average cost has already surpassed that of 2021, indicates escalating healthcare expenses. This could be due to a variety of factors, including advanced medical technologies, inflation, and increased labor costs.

- **What is the trend for the mortality rate?**
  - There has been a consistent decrease in the number of deaths and the mortality rate since 2011.
  - The highest mortality rate was recorded in February 2011, reaching 44.71%.
  - Procedures such as combined chemotherapy and radiation therapy, and assessment of health and social need, had a 100% mortality rate during this period, suggesting a possible outbreak or critical incident.
  - The overall downward trend in mortality rates reflects significant improvements in medical care and patient safety initiatives.

- **What are the most common reasons for encounters?**
  - The encounter category "Encounter for problem" had the highest number of visits, totaling over 4,300 visits.
  - This indicates that a significant portion of hospital resources is dedicated to diagnosing and managing various health issues that bring patients to the hospital.

- **How many procedures are covered by insurance?**
  - Out of 163 distinct procedures, 144 had insurance coverage, demonstrating a high level of support from insurance providers for medical procedures.
  - However, several critical procedures, including admissions to burn units, long stay hospitals, ICU admissions, appendectomies, fine needle aspirations of the lungs, and thoracentesis, lacked coverage.
  - This gap in coverage highlights areas where patients might face significant out-of-pocket expenses, potentially impacting their access to necessary care.

- **Which procedures have the highest readmission rates?**
  - Certain procedures, such as the alpha-fetoprotein test, had a readmission rate of 100%.
  - This indicates areas where clinical protocols might need to be reviewed and improved to reduce the likelihood of patient readmission.

- **Which payers have the highest and lowest coverage percentages?**
  - Medicaid demonstrated the highest percentage coverage at 94.01%, reflecting its extensive role in patient care.
  - Despite this, Medicare covered over 11,000 encounters and 20,000 procedures, with total claimed costs exceeding $19 million, highlighting its significant financial contribution to patient care and its importance in the healthcare system.

By leveraging Power BI for data visualization and analysis, I delivered a comprehensive KPI report that provided the executive team at Massachusetts General Hospital with actionable insights, aiding them in making informed decisions to improve hospital operations and patient care.

- **RECOMMENDATIONS**

   - Implement targeted follow-up and discharge programs for seniors and Native populations to reduce readmissions by enhancing post-discharge care.
   - Continue improving hospital efficiency to maintain or reduce stay durations, particularly for non-ICU cases.
   - Focus on refining care protocols for high-risk procedures and invest in research to improve outcomes for critically ill patients.
   - Explore cost-control measures such as optimizing resource allocation, reducing unnecessary tests, and improving procurement efficiency to manage rising healthcare costs.
   - Continue patient safety initiatives and focus on improving protocols for high-mortality procedures to sustain the downward trend in mortality rates.
   - Work with insurers to expand coverage for essential procedures like ICU admissions and appendectomies, reducing financial burdens on patients.
   - Review and refine clinical protocols for procedures with high readmission rates to minimize unnecessary repeat visits.
   - Ensure continuous collaboration with Medicaid and Medicare to maintain coverage levels and financial support, especially for critical and high-cost care.

[Click Link for full report](https://app.powerbi.com/groups/me/reports/cf5bba41-1a59-4452-9094-3e8577aa9c61/9bb7dcc2dd4123a8a7db?experience=power-bi)
