# ✈️ British Airways Customer Review Analysis

> **A Power BI Dashboard Project developed during my Data Analytics Internship at Labmentix**

---

## 📌 Project Overview

This project analyzes customer reviews of **British Airways** using **Power BI** to uncover insights into passenger satisfaction, service quality, and operational performance.

The project transforms raw customer review data into interactive dashboards that enable stakeholders to monitor key performance indicators, identify areas requiring improvement, and support data-driven decision-making.

The project demonstrates the complete Business Intelligence workflow—from data cleaning and transformation to dashboard development and insight generation.

---

## 🎯 Business Objectives

The primary objectives of this project were to:

- Analyze overall customer satisfaction.
- Evaluate different service categories provided by British Airways.
- Compare passenger experiences across traveller and seat types.
- Identify trends based on aircraft, routes, and customer verification.
- Develop interactive dashboards for business decision-making.

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| Total Reviews | 1,324 |
| Time Period | March 2016 – October 2023 |
| Countries | 56 |
| Aircraft Types | 104 |
| Routes | 805 |
| Source | British Airways Customer Reviews |

The dataset contains customer feedback including:

- Overall Rating
- Seat Comfort
- Cabin Staff Service
- Food & Beverages
- Ground Service
- Entertainment
- Value for Money
- Traveller Type
- Seat Type
- Country
- Aircraft
- Route
- Recommendation Status
- Trip Verification Status

---

# 🧹 Data Preparation

The dataset was prepared using **Power Query** before visualization.

### Data Cleaning

✔ Removed unnecessary columns

✔ Corrected data types

✔ Renamed columns where required

✔ Replaced **-1 values with Null** for unavailable services

✔ Cleaned text fields

✔ Created a Date Table

✔ Built relationships between tables

✔ Unpivoted service rating columns for comparative analysis

---

# 📐 DAX Measures

Several reusable DAX measures were created to support dashboard calculations, including:

- Total Reviews
- Overall Rating
- Recommendation Rate
- Total Countries
- Aircraft Types
- Total Routes
- Verified Reviews
- Average Seat Comfort
- Average Cabin Staff Service
- Average Food Rating
- Average Entertainment
- Average Ground Service
- Average Value for Money

---

# 📈 Dashboard 1 – Executive Overview

![Executive Overview](https://github.com/Kaustubh-Sahu/British-Airways-Customer-Review-Analysis/blob/a6fa81b75d11224b221a52fd78d904f8a6eda19d/Dashboard%20Snapshots/Executive%20Overview.png)

### Purpose

Provides a high-level overview of customer satisfaction and overall airline performance.

### Key Visualizations

- KPI Cards
- World Map
- Rating Distribution
- Recommendation Analysis
- Customer Rating Trend
- Interactive Slicers

### Key Insights

- British Airways received reviews from customers across multiple countries.
- Overall customer satisfaction remains moderate.
- Recommendation rates vary across different traveller types.
- Customer ratings change over time.

---

# 🍽 Dashboard 2 – Service Quality Analysis

![Service Quality Analysis](https://github.com/Kaustubh-Sahu/British-Airways-Customer-Review-Analysis/blob/a6fa81b75d11224b221a52fd78d904f8a6eda19d/Dashboard%20Snapshots/Service%20Quality%20Analysis.png)

### Purpose

Evaluates the performance of different airline services.

### Key Visualizations

- Service Rating Comparison
- Traveller Type Analysis
- Seat Type Analysis
- Recommendation Analysis
- Service Matrix

### Key Insights

- Cabin Staff Service received the highest customer ratings.
- Food Quality and Entertainment received comparatively lower ratings.
- Premium cabin passengers generally reported better experiences.
- Service quality differs across seat types.

---

# ✈ Dashboard 3 – Aircraft & Customer Insights

![Aircraft & Customer Insights](https://github.com/Kaustubh-Sahu/British-Airways-Customer-Review-Analysis/blob/a6fa81b75d11224b221a52fd78d904f8a6eda19d/Dashboard%20Snapshots/Aircraft%20%26%20Customer%20Insights.png)

### Purpose

Analyzes operational factors affecting customer satisfaction.

### Key Visualizations

- Aircraft Performance
- Route Analysis
- Verified vs Non-Verified Reviews
- Trip Verification Analysis
- Country Treemap

### Key Insights

- Customer satisfaction varies across aircraft types.
- Flight routes perform differently in terms of passenger ratings.
- Verified reviews provide reliable customer feedback.
- Review distribution differs across countries.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations are suggested:

- Improve Food Quality and In-flight Entertainment.
- Maintain the high standards of Cabin Staff Service.
- Monitor underperforming aircraft and routes.
- Encourage more verified customer reviews.
- Use dashboard insights for continuous performance monitoring and decision-making.

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Power Query
- Dashboard Design
- Data Visualization
- Business Intelligence
- KPI Development
- Analytical Thinking

---

# 📂 Repository Structure

```
British-Airways-Customer-Review-Analysis
│
├── Dashboard Screenshots
├── Dataset
├── Power BI Project
├── Presentation
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📸 Project Preview

| Dashboard | Description |
|------------|-------------|
| Executive Overview | Overall business performance and customer satisfaction |
| Service Quality Analysis | Evaluation of airline services |
| Aircraft & Customer Insights | Operational and customer behaviour analysis |

---

# 📁 Project Files

| Folder | Description |
|----------|-------------|
| Dataset | Source dataset used for analysis |
| Power BI Project | PBIX project file |
| Dashboard Screenshots | Exported dashboard images |
| Presentation | Project presentation and documentation |

---

# 📖 Learning Outcomes

Through this project, I gained hands-on experience in:

- Power BI Dashboard Development
- Data Cleaning using Power Query
- Data Modeling
- Writing DAX Measures
- Business Intelligence Reporting
- Interactive Dashboard Design
- Business Insight Generation
- Presenting analytical findings to stakeholders

---

# 👨‍💻 About Me

**Kaustubh Sahu**

Data Analytics Enthusiast passionate about transforming raw data into meaningful business insights using **Power BI, SQL, Python, Excel, and Data Visualization**.

---

## ⭐ If you found this project useful, consider giving it a star!
