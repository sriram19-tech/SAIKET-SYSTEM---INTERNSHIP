# SAIKET-SYSTEM---INTERNSHIP

 📊 Customer Churn Analysis — Business Analysis Internship

> **Internship at:** SaiKet Systems | Innovate. Elevate. Excel.  
> **Intern:** Sriram S  
> **Role:** Business Analysis Intern  
> **Duration:** June 2026  

---

## 🧾 Project Overview

This project focuses on analyzing customer churn behavior using a real-world telecom dataset. The goal is to uncover patterns and trends that drive customer churn — helping businesses take proactive retention decisions through data-driven insights.

---

## 📁 Project Structure

```
customer-churn-analysis/
│
├── task1.py                   # Data Exploration
├── task2.py                   # Data Cleaning
├── task3.py                   # EDA & Visualization
├── task4.py                   # Customer Segmentation
├── task5.py                   # Advanced Churn Analysis
│
├── customer_data.csv          # Raw dataset
├── cleaned_customer_data.csv  # Cleaned dataset (output of Task 2)
│
├── outputs/                   # All generated plots & visualizations
│   ├── histogram.png
│   ├── boxplot.png
│   ├── churn_pie.png
│   ├── heatmap.png
│   ├── task4_tenure_donut.png
│   ├── task4_monthly_charges_clustered.png
│   ├── task5_tenure_churn.png
│   ├── task5_demographics.png
│   ├── task5_payment_contract.png
│   └── task5_tenure_trend.png
│
└── README.md
```

---

## ✅ Tasks Completed

### Task 1 — Data Exploration
- Loaded the raw dataset using Pandas
- Inspected first 10 rows, data types, missing values and dataset info

### Task 2 — Data Cleaning
- Converted `TotalCharges` to numeric and filled missing values with median
- Removed duplicate rows
- Standardized column names to lowercase with underscores
- Saved cleaned data as `cleaned_customer_data.csv`

### Task 3 — Exploratory Data Analysis (EDA)
- Computed summary statistics (mean, median, mode, std, min, max)
- Generated **Histograms** for all numerical columns
- Generated **Box Plots** to detect outliers
- Created **Churn vs Non-Churn Pie Chart**
- Built **Correlation Heatmap** to find relationships between variables

### Task 4 — Customer Segmentation
- Segmented customers by tenure: `0-12 months`, `13-36 months`, `37+ months`
- Built a **Donut Chart** showing customer distribution by tenure segment
- Built a **Clustered Bar Chart** comparing average monthly charges by tenure & churn status

### Task 5 — Advanced Churn Analysis
- **Tenure Group Analysis** — Churn rate across different tenure buckets
- **Demographic Analysis** — Churn by Gender & Senior Citizen status
- **Payment Method Analysis** — Churn rate across payment types
- **Contract Type Analysis** — Month-to-month vs longer contracts
- **Tenure Trend Analysis** — Churn rate vs monthly charges over tenure ranges

---

## 💡 Key Insights

| Finding | Detail |
|--------|--------|
| 🔴 Highest Churn Group | Customers with **0-12 months** tenure |
| 💳 Riskiest Payment Method | **Electronic Check** users churn the most |
| 📄 Riskiest Contract Type | **Month-to-Month** contracts have highest churn |
| 👴 Senior Citizens | Churn at a significantly higher rate than non-seniors |
| 📈 Long-tenure Customers | Much lower churn — loyalty increases with tenure |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Pandas | Data manipulation & cleaning |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| NumPy | Numerical operations |

---

## 📊 Sample Visualizations

> Plots are saved in the `outputs/` folder.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis

# Install dependencies
pip install pandas matplotlib seaborn numpy

# Run tasks in order
python task1.py
python task2.py
python task3.py
python task4.py
python task5.py
```

---

## 🏢 About the Internship

This project was completed as part of the **Business Analysis Internship at SaiKet Systems**.  
The internship provided hands-on experience in real-world data analysis, visualization, and deriving actionable business insights from raw datasets.

---

* by Sriram S*
