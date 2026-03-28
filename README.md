# [Customer Segmentation Analysis 🛍️]: Identifying actionable cohorts and fueling target marketing 

### 📋 Overview
The Goal: Identify distinct actionable groups based on consumer value to fuel marketing strategies.
The Impact: Identified 4 distinct customer groups using RFM analysis, and identified market composition based on CLV and other key performance indicators.
### Tech & Methods: ⚙️
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

* Languages/Tools: R, Tableau
* Libraries: tidyverse, lubridate, plotly
* Concepts: K-Means, Clustering, RFM Analysis, Customer Lifetime Value, WCSS
  
### 🗺️ Project Architecture

* Data Ingestion: Collected by the University of California, Irvine, for a European retailer between 01/12/2010 and 19/12/2011.
* Processing/Storage: Downloaded and stored as a CSV file, and cleaned/processed in R-Studio.
* Analysis/Modeling: Cohorts were separated based on transaction frequency, how recent their last transaction was, and how much overall spending they have conducted with the retailer. After grouping, Customer lifetime values were calculated to determine the value of each cohort.
*  Delivery: The results were summarized in a Tableau dashboard, identifying the market composition regarding cohort and customer lifetime value.

### 📊 Key Insights & Outcomes
* Insight 1: Identified four customer cohorts, highlighting a 5.4% churn risk.
* Insight 2: Automated reporting of market composition, displaying cohort size, location, and characteristics.

---
### 📂 Repository Structure

* data: Segmented_data_irvine.csv
* notebooks: Customer_Segmentation.pdf 
* src: Customer_Segmentation.qmd
* Images/Dashboards: CustomerSegmentationDashboard.png
