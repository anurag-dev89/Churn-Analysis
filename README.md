# 📊 Customer Churn Analysis & Business Intelligence Dashboard

## 🚀 Project Overview

This project focuses on analyzing customer churn behavior for a subscription-based digital platform using Python, SQL, SQLite, Pandas, and Tableau. The objective was to identify key drivers of customer attrition, quantify revenue impact, measure customer engagement, and generate actionable business recommendations through data-driven insights.

The project follows a complete analytics workflow including data modeling, data cleaning, feature engineering, KPI development, exploratory analysis, business intelligence reporting, and interactive dashboard creation.

---

## 🎯 Business Problem

Customer churn directly impacts revenue, customer lifetime value (CLTV), and long-term business growth. The goal of this project was to:

* Identify customers likely to churn.
* Measure revenue loss due to customer attrition.
* Analyze churn trends across states, plans, contracts, and demographics.
* Evaluate customer support interactions and escalation patterns.
* Provide actionable recommendations to improve retention and reduce revenue leakage.

---

## 🛠️ Technology Stack

### Programming & Analytics

* Python
* Pandas
* NumPy
* SQLite
* SQL

### Data Visualization

* Tableau Public / Tableau Desktop

### Development Tools

* Jupyter Notebook
* Git
* GitHub

---

## 🗄️ Database Design

The project uses a relational database consisting of three interconnected tables.

### 1. Customer Table (`db_customer`)

| Column        |
| ------------- |
| customerid    |
| customer_name |
| country       |
| state         |
| gender        |
| dob           |

---

### 2. Subscription Table (`db_subscription`)

| Column                  |
| ----------------------- |
| customerid              |
| subscription_start_date |
| subscription_type       |
| renewal_date            |
| plan_type               |
| contract_type           |
| cancellation_date       |
| cancellation_reason     |
| monthly_charges         |
| cltv                    |
| churn_score             |
| churn_flag              |

---

### 3. Support Table (`db_support`)

| Column         |
| -------------- |
| customerid     |
| complaint_date |
| escalations    |
| csat_score     |

---

## 🔄 Data Engineering & Preparation

The following preprocessing and transformation tasks were performed:

* Merged customer, subscription, and support datasets using customer ID.
* Standardized categorical values.
* Cleaned inconsistent gender values.
* Removed unnecessary columns.
* Handled missing values and null records.
* Created complaint frequency metrics.
* Generated churn risk segmentation.
* Calculated customer tenure.
* Built analytical features for dashboard reporting.

---

## 📈 Key Performance Indicators (KPIs)

The project calculates multiple business KPIs including:

### Customer Metrics

* Total Customers
* Churned Customers
* Retained Customers
* Churn Rate
* Retention Rate
* Average Customer Tenure

### Revenue Metrics

* Total Revenue
* Revenue at Risk
* Monthly Recurring Revenue (MRR)
* Average Revenue Per User (ARPU)
* Customer Lifetime Value (CLTV)

### Support Metrics

* Escalation Rate
* Average Complaints per Customer
* Average CSAT Score
* Complaint Frequency

### Risk Metrics

* Churn Score Analysis
* Churn Risk Segmentation
* Revenue Exposure by Risk Category

---

## 📊 Tableau Dashboard

An interactive Tableau dashboard was developed to enable business users to explore churn patterns and customer behavior.

### Dashboard Components

#### KPI Cards

* Total Customers
* Churn Rate
* Retention Rate
* Total Revenue
* Revenue at Risk

#### Visualizations

* Churn by State
* Churn by Plan Type
* Revenue by Subscription Type
* Monthly Churn Trend
* Churn by Gender
* Revenue at Risk by State
* Churn Risk Heatmap
* Customer Satisfaction (CSAT) Analysis

#### Interactive Filters

* State
* Gender
* Plan Type
* Subscription Type
* Contract Type

All dashboard components are dynamically linked, enabling users to perform drill-down analysis across different customer segments.

---

## 🔍 Analytical Approach

The project combines descriptive analytics and business intelligence techniques to answer the following questions:

* Which customer segments are most likely to churn?
* Which states contribute the highest churn volume?
* Which plans generate the highest customer attrition?
* How much revenue is currently at risk?
* What role do support escalations play in customer churn?
* How does customer satisfaction influence retention?

---

## 📌 Business Insights

Key findings extracted from the analysis include:

* Churn patterns vary significantly across geographical regions.
* Certain subscription plans contribute disproportionately to customer attrition.
* High-risk customers represent a measurable portion of revenue exposure.
* Support escalations are strongly associated with increased churn probability.
* Customer satisfaction scores provide early indicators of retention risk.
* Revenue concentration among specific customer segments highlights opportunities for targeted retention campaigns.

---

## 💡 Business Recommendations

Based on the analysis:

1. Prioritize retention efforts for high-risk customers with high CLTV.
2. Investigate regions exhibiting elevated churn behavior.
3. Improve support resolution processes to reduce escalations.
4. Design targeted retention campaigns for vulnerable subscription segments.
5. Monitor churn score trends proactively to prevent revenue loss.
6. Focus customer success initiatives on high-value accounts.

---

## 📁 Repository Structure

```text
Customer-Churn-Analysis/
│
├── customer_churn.db
├── churn_analysis.ipynb
├── customer_churn_cleaned.csv
├── Customer_Churn_Dashboard.twbx
├── Customer_Churn_Report.pdf
├── Dashboard.png
├── README.md
│
└── assets/
    └── dashboard_screenshots
```

---

## 📷 Dashboard Preview

Add your exported Tableau dashboard screenshot below:

```markdown
![Customer Churn Dashboard](dashboard.png)
```

---

## 🎓 Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis (EDA)
* KPI Development
* Customer Segmentation
* Churn Analytics
* Revenue Analysis

### Data Engineering

* Data Cleaning
* Data Transformation
* Feature Engineering
* Relational Data Modeling

### Business Intelligence

* Dashboard Development
* Interactive Reporting
* Data Storytelling
* Executive Reporting

### Technical Skills

* Python
* Pandas
* SQL
* SQLite
* Tableau
* Git & GitHub

---

## 👨‍💻 Author

**Anurag Patel**

Aspiring Data Analyst | Python | SQL | Tableau | Data Analytics

This project was developed as a portfolio project to demonstrate end-to-end analytics, business intelligence, and data storytelling capabilities using real-world customer churn analysis techniques.
