# Data Mining Project Guide

**Author:** Hope Kimandi_317


**Project Topic:** Banking Customer Behavior Analysis

**Structure**
DataMining_GroupProject_Hope/ 
├── data/ 
│   ├── raw/ 
│   ├── transformed/ 
│   └── final/ 
├── notebooks/ 
│   ├── 1_extract_transform.ipynb 
│   ├── 2_exploratory_analysis.ipynb 
│   ├── 3_data_mining.ipynb 
│   └── 4_insights_dashboard.ipynb 
├── report/ 
│   ├── images.png/ 
│   ├── executive_summary.pdf  
|   └── presentation.pptx
├── requirements.txt 
├── .gitignore 
└── README.md 

**Data Information:**
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

**Key Questions Explored:**

1. What are the key demographic and transactional factors influencing customer behavior?
2. Which customer segments are more likely to subscribe to a bank product?
3. How do different marketing campaigns affect customer response?
4. What patterns exist in subscription trends, customer activity, and churn rates?

---

## ETL (Extract, Transform, Load) Summary

1. **Extraction:**

   * Data was collected from the `bank_additional_transformed.xlsx` dataset containing customer demographic information, previous interactions, and transaction history.

2. **Transformation:**

   * Cleaning: Handling missing values, correcting inconsistent entries, and standardizing formats.
   * Encoding: Converting categorical variables into numeric formats for analysis.
   * Feature Engineering: Adding calculated fields to support analysis (e.g., subscription status, campaign response rate).

3. **Loading:**

   * Transformed data was saved into structured tables for analysis using Python and Pandas, ready for statistical and data mining techniques.

---

## Techniques Used

**Statistical Analysis:**

* Descriptive statistics: Mean, median, mode, standard deviation.
* Frequency analysis: To determine distribution of categorical variables.
* Correlation analysis: To identify relationships between numerical features.

**Data Mining Techniques:**

* Association rule mining: To identify relationships between different customer attributes.
* Classification: To predict subscription outcomes based on customer features.
* Clustering: To segment customers based on behavioral and demographic similarities.

---

## Tools Used

* **Python:** For data cleaning, transformation, and analysis.
* **Pandas & NumPy:** Data manipulation and numerical computation.
* **Matplotlib & Seaborn:** Visualization of trends and patterns.
* **Jupyter Notebook:** Interactive analysis and reporting of results.
* **Excel:** Initial data inspection and minor transformations.

---

## Instructions to Run Notebooks

1. Ensure **Python 3.x** is installed on your system.
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```
3. Download the dataset and place it in the following path:

   ```
   C:\Users\lenovo\OneDrive\Desktop\KEndy\ASSIGNMENTS\DSA Assignments\DSA 2040\Data mining_group project_Hope\DATA\bank_additional_transformed.xlsx
   ```
4. Open the **Jupyter Notebook** provided in the project folder.
5. Run the notebook cells sequentially to replicate the analysis and visualizations.
6. Review each section for ETL process, statistical insights, and data mining results.

---
## Project Summary

This project focuses on **data mining and analysis of a banking dataset** to extract meaningful insights and support decision-making. The main objective is to understand customer behavior, patterns, and factors affecting banking operations.


**Visualizations** 

<img width="600" height="400" alt="age_distribution" src="https://github.com/user-attachments/assets/b16679ba-21b5-495f-a388-c346078ac1c8" />
<img width="800" height="400" alt="job_vs_subscription" src="https://github.com/user-attachments/assets/f7c02da8-5af1-4561-890b-497190dd3d1c" />
<img width="800" height="400" alt="monthly_trends" src="https://github.com/user-attachments/assets/1dac226c-eb3d-45f9-b14b-995b6b3b5b34" />
<img width="600" height="400" alt="prev_outcome" src="https://github.com/user-attachments/assets/f8116f76-29b8-4046-9028-eb8c8612a623" />
<img width="500" height="500" alt="subscription_pie" src="https://github.com/user-attachments/assets/ac1fe952-3049-4129-849b-8a4bb8138145" />




