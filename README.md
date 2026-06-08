<<<<<<< HEAD
# 🛒 E-Commerce Sales Analysis — Project 01

> **Analysing 12 months of real Brazilian e-commerce data to uncover revenue trends, regional patterns, and customer behaviour using Python.**

---

## 📌 Project Overview

| Field | Details |
|-------|---------|
| **Dataset** | Olist Brazilian E-Commerce (Kaggle) |
| **Records** | 96,477 delivered orders |
| **Period** | October 2016 — August 2018 |
| **Total Revenue** | R$ 19,881,945 |
| **Top Category** | Bed, Bath & Table |
| **Peak Month** | November 2017 (Black Friday) |
| **Tools Used** | Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook |

---

## 📂 Project Structure

```
project01/
│
├── 📓 analysis.ipynb              ← Main Jupyter Notebook (all code + insights)
├── chart1_category_revenue.png
├── chart2_monthly_trend.png
├── chart3_regional_sales.png
├── chart4_order_histogram.png
├── chart5_review_pie.png
├── chart6_heatmap.png
├── 🖥️ dashboard.png               ← 1-page KPI summary dashboard
├── olist_orders_dataset.csv
├── olist_order_items_dataset.csv
├── olist_products_dataset.csv
├── olist_customers_dataset.csv
├── olist_order_reviews_dataset.csv
├── olist_order_payments_dataset.csv
├── product_category_name_translation.csv
│
└── README.md
```

---

## 🗃️ Dataset

- **Source:** [Olist Brazilian E-Commerce Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **License:** CC BY-NC-SA 4.0
- **Description:** Real anonymised transactional data from Olist, Brazil's largest department store marketplace. Contains orders, products, customers, sellers, payments, and reviews across 2016–2018.

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/project01-ecommerce-analysis.git
cd project01-ecommerce-analysis
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Download the dataset
Download from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and place all CSV files inside the `data/` folder.

### 4. Run the notebook
```bash
jupyter notebook analysis.ipynb
```
Run all cells top to bottom — charts and insights will generate automatically.

---

## 🔍 Analysis Questions Answered

| # | Question | Finding |
|---|----------|---------|
| 1 | Which product category has the highest revenue? | **Bed, Bath & Table** — R$ 1.75M |
| 2 | Which month had peak sales? | **November 2017** — R$ 1.55M (Black Friday) |
| 3 | Which region performs best? | **São Paulo (SP)** — R$ 7.5M (~38% of total) |
| 4 | What is the average order value trend? | Most orders fall between **R$ 100–300** |
| 5 | What is the customer review score distribution? | **57.5% gave 5 stars**, but 11.4% gave 1 star |

---

## 📈 Visualisations

| Chart | Type | Insight |
|-------|------|---------|
| Category Revenue | Bar Chart | Top 10 categories by total revenue |
| Monthly Trend | Line Chart | Sales growth from Oct 2016 to Aug 2018 |
| Regional Sales | Bar Chart | Revenue breakdown by Brazilian state |
| Order Value Distribution | Histogram | Most orders clustered under R$ 500 |
| Review Score Distribution | Pie Chart | Majority satisfied, notable 1-star segment |
| Category vs Month | Heatmap | Seasonal revenue patterns by category |

---

## 💡 Key Business Insights

**1. Bed, Bath & Table leads — but the top 3 are very close**
The top three categories (bed/bath, health/beauty, computers) are within R$ 200K of each other, suggesting a diverse, non-dominant product mix. Cross-category bundling could increase basket size.

**2. Black Friday is the single biggest revenue driver**
November 2017 spiked 55% above the monthly average. Inventory and marketing should be planned 6–8 weeks in advance of November each year.

**3. São Paulo is the core market — other states are underserved**
SP accounts for ~38% of total revenue alone. States like MG and RS show moderate demand but receive far less marketing focus — a clear growth opportunity.

**4. Customers are price-sensitive — most orders under R$ 500**
The heavily right-skewed order distribution suggests budget-conscious shoppers dominate. Bundle deals and "spend more, save more" campaigns could lift the average order value.

**5. Polarised reviews demand urgent attention**
57.5% of customers gave 5 stars, but 11.4% gave 1 star. This gap represents serious churn risk. A post-delivery feedback loop within 48 hours of delivery could prevent negative public reviews.

---

## 🤔 Most Surprising Finding

The most unexpected result was that **"Bed, Bath & Table"** — a completely ordinary household category — outperformed electronics and tech accessories in total revenue. On a digital marketplace, tech products were expected to dominate. Additionally, the sheer dominance of **São Paulo** (nearly 3× the revenue of second-place Rio de Janeiro) revealed how geographically concentrated Brazilian e-commerce demand truly is.

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualisation-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red?logo=jupyter)

---

## 👤 Author

**Subham Sahoo**
- GitHub: [subho72](https://github.com/Subho72)
- Project: Data Analysis — Project 01

---

*This project was completed as part of a structured Data Analysis learning program.*
=======
# PROJECT_01
Python-based analysis of 96K+ Brazilian e-commerce orders — revenue trends, regional insights, customer reviews &amp; interactive dashboard using Pandas, Matplotlib and Seaborn.
>>>>>>> 0eb137e0f305ccd00298db431a25e8fbea4245af
