
# **Telecom Customer Churn Prediction**

## **Project Overview**

Customer churn is one of the most critical challenges for telecom companies, directly affecting revenue and growth. This project focuses on predicting which customers are at risk of leaving, understanding the drivers behind churn, and proposing actionable retention strategies.

By leveraging a rich dataset of telecom customers, service usage, and billing data, this project combines **data cleaning**, **exploratory analysis**, **predictive modeling**, and **business insights** to provide a comprehensive solution for reducing churn.

---

## **Business Problem**

* **Goal:** Identify customers likely to churn before they leave.
* **Objectives:**

  1. Predict which customers are at risk of churn.
  2. Understand the key behavioral, financial, and service-related factors driving churn.
  3. Develop targeted retention strategies for high-risk customer segments.
  4. Build a Power BI dashboard to monitor churn in real-time for stakeholders.

---

## **Dataset**

The project uses a **telecom customer churn dataset** with 7,043 customers and 38 features covering:

* **Demographics:** Age, Gender, Marital Status, Dependents, Region
* **Service Usage:** Phone, Internet, Add-ons (Streaming, Security, Backup, Tech Support)
* **Billing & Financials:** Monthly Charges, Total Revenue, Refunds, Extra Charges
* **Behavior & Engagement:** Tenure, Referrals, Last activity
* **Churn Labels:** Customer Status (Stayed / Churned / Joined), Churn Reason, Churn Category

**Key Feature:** `Customer Status` serves as the **target variable** for predictive modeling (Churned = 1, Stayed = 0).

---

## **Project Workflow**

1. **Data Understanding**

   * Explore dataset structure, types, and missing values
   * Understand target variable distribution
   * Identify key features for modeling

2. **Data Cleaning & Preprocessing**

   * Handle missing values
   * Encode categorical variables
   * Filter out “Joined” customers
   * Feature engineering for engagement, usage, and financial metrics

3. **Exploratory Data Analysis (EDA)**

   * Analyze churn patterns by contract, service type, monthly charges, tenure, and demographics
   * Visualize high-risk segments and top churn reasons
   * Identify correlations and feature importance

4. **Predictive Modeling**

   * Train Logistic Regression and Random Forest models
   * Evaluate models with Accuracy, Precision, Recall, and ROC-AUC
   * Identify top predictors of churn

5. **Churn Scoring & Segmentation**

   * Assign churn probabilities to all customers
   * Segment customers into High, Medium, Low risk
   * Prioritize retention actions for each segment

6. **Retention Strategy Recommendations**

   * Targeted retention campaigns for high-value customers
   * Engagement strategies for low-activity customers
   * Actionable insights based on churn reasons

7. **Power BI Dashboard**

   * KPI cards: Churn Rate, High-Risk Customers, Lost Revenue, Average Tenure of Churners
   * Charts: Churn by Contract, Internet Type, Monthly Charge, Tenure, Churn Reason
   * Tables: Top high-risk customers and recommended retention actions

---

## **Tech Stack & Tools**

* **Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **SQL:** Optional for querying and aggregating raw data
* **Power BI:** Dashboard visualizations and KPI tracking
* **GitHub:** Project versioning and portfolio showcase

---

## **Project Deliverables**

1. **Python Notebooks:**

   * Data Cleaning & Feature Engineering
   * Exploratory Data Analysis
   * Churn Modeling & Scoring

2. **CSV Outputs:**

   * Feature-engineered dataset
   * Customer churn probability scores

3. **Power BI Dashboard:**

   * Interactive, real-time monitoring of churn KPIs and high-risk segments

4. **Portfolio Case Study / Insights Report:**

   * Clear business insights and retention recommendations
   * Visualizations highlighting churn drivers

---

## **Project Impact**

* Enable telecom companies to **proactively retain at-risk customers**
* Reduce revenue loss from churn
* Inform marketing, product, and customer success teams with **data-driven strategies**
* Showcase advanced **data analysis, modeling, and business storytelling skills** for Customer Insights roles

---


Do you want me to do that next?
