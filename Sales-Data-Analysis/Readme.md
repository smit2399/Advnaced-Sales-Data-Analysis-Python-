# **📊 Advanced Sales Data Analysis & Business Insights**

This project applies advanced data science techniques to a sales dataset in order to uncover actionable insights, predict future trends, and enhance business decision-making. The analysis integrates data cleaning, statistical testing, predictive modeling, machine learning, and interactive visualizations using Tableau.

## **🧠 Project Objective**

To transform raw sales transaction data into meaningful insights that inform strategic business actions such as customer retention, inventory optimization, and targeted marketing.

## **🗂️ Dataset Overview**

The dataset contains enriched sales records with the following features:

* Customer\_ID  
* Product\_ID  
* Date  
* Total\_Spend  
* Marketing\_Spend  
* Region  
* Promotion  
* Churn\_Status

## **🔍 Phase 1: Data Cleaning & Preprocessing**

* Handled missing values, duplicates, and inconsistent data types.  
* Standardized categorical columns.  
* Performed exploratory data analysis to detect outliers and anomalies.  
* Final dataset: **16 rows x 8 columns**

## **📈 Phase 2: Exploratory Data Analysis (EDA)**

* Visualized churn distribution and customer behavior across regions.  
* Identified correlations:  
  * **High correlation** between Marketing\_Spend and Purchase\_Frequency.  
* Key Insight:  
  * South and West regions showed higher churn rates.  
  * Marketing investment trends impacted churn and sales performance.

## **🔮 Phase 3: Predictive Modeling**

### **🧮 Linear Regression**

* Predicted Total\_Spend using Marketing\_Spend and Seasonality\_Index.  
* Evaluation metrics: **R² Score** and **RMSE**.

### **🚪 Logistic Regression**

* Predicted customer churn (Yes/No) based on behavioral features.  
* Evaluated using accuracy, classification report, and confusion matrix.

### **📆 ARIMA Forecasting**

* Modeled monthly sales trends and forecasted revenue for the next 6 months.  
* Used to inform inventory and financial planning.

## **📊 Phase 4: Statistical Analysis**

### **ANOVA**

* Tested if average sales differ across regions.  
* **Result**: Checked significance using p-values.

### **T-Test**

* Assessed whether promotions significantly impacted sales.  
* **Result**: Promotion periods showed statistically significant uplift in sales.

### **Factor Analysis**

* Extracted hidden drivers behind customer purchasing behavior.  
* Simplified multiple variables into core influencing factors.

## **🤖 Phase 5: Machine Learning for Customer Segmentation**

### **🌳 Decision Trees**

* Segmented customers by churn likelihood.  
* Visualized rules driving churn, enabling targeted retention strategies.

### **🎯 K-Means Clustering**

* Grouped customers into segments (e.g., high spenders, budget-conscious).  
* Visualized segments using PCA for clear interpretation.

### **🌲 Random Forest**

* Improved churn prediction accuracy compared to logistic regression.  
* Captured complex patterns in spending and frequency.

## **📊 Phase 6: Interactive Dashboards in Tableau**

### **1\. Sales Performance Dashboard**

* View sales by region, category, and over time.  
* Identify peak periods and top-performing segments.

### **2\. Customer Segmentation Dashboard**

* Visualize clusters and decision tree paths.  
* Supports marketing personalization and loyalty campaigns.

### **3\. Churn Analysis Dashboard**

* Track churn trends and risk factors.  
* Enable early retention interventions.  
  


### **4\. Forecasting Dashboard**

* Compare actual vs. forecasted sales.  
* Plan inventory and budget with confidence.

## **💡 Business Insights & Recommendations**

### **Key Findings:**

1. **High-Value Customers Identified**  
    → Cluster of loyal, high-spend, low-churn users.  
2. **Seasonal Sales Trends Detected**  
    → Strong spikes during Q4 and mid-year events.  
3. **Churn Risk Indicators Found**  
    → Low-frequency, low-spend users more likely to churn.

### **Strategic Actions:**

* 🎯 **Targeted Marketing**  
   → Incentivize loyal customers, re-engage at-risk segments.  
* 📦 **Inventory Optimization**  
   → Align procurement with seasonal forecasts.  
* ❤️ **Customer Retention Initiatives**  
   → Launch loyalty programs, personalized offers, and churn-risk tracking.

## **🛠️ Tools & Technologies**

* **Python**: Data preprocessing, modeling, and statistical analysis.  
* **Pandas, NumPy, Scikit-learn, Statsmodels**: Core analysis libraries.  
* **ARIMA, Random Forest, Logistic Regression, K-Means**: Modeling techniques.  
* **Tableau**: Interactive dashboarding and storytelling.

