#  Customer Shopping Behavior Analysis | Data Analytics Project

## 1. Overview

This project analyzes **customer shopping behavior in retail data** to understand purchasing patterns and improve **sales performance, customer engagement, and loyalty**. The analysis focuses on how factors such as **discount usage, customer demographics, product ratings, seasons, and shipping methods** influence buying decisions. The goal is to convert raw transactional data into **actionable business insights** using Python, SQL, and Power BI.

## 2. Dataset

* **Rows:** 3,900
* **Columns:** 18
* **Missing Values:** 37 (Review Rating column)

### Key Data Features:

* Customer demographics (Age, Gender, Location, Subscription Status)
* Purchase details (Product, Category, Amount, Season, Size, Color)
* Shopping behavior (Discounts, Promo Codes, Frequency, Reviews)
* Shipping and engagement patterns

---

## Tools & Technologies

| Tool         | Purpose                        |
| ------------ | ------------------------------ |
| Python       | Data cleaning, EDA             |
| Pandas       | Data manipulation              |
| MySQL Server | Data storage & SQL analysis    |
| SQL          | Business queries & insights    |
| Power BI     | Dashboard visualization        |
| Gamma        | Report & presentation creation |

---

## Project Steps

### 1. Data Loading (Python)

* Imported dataset using Pandas
* Explored structure using `info()` and `describe()`

### 2. Data Cleaning

* Handled missing values in Review Rating column using category-wise median
* Standardized column names (snake_case format)
* Removed redundant columns
* Ensured data consistency for analysis

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer purchasing behavior
* Identified spending patterns and trends
* Performed feature engineering:

  * Age group segmentation
  * Purchase frequency calculation

### 4. Database Integration (MySQL)

* Exported cleaned dataset into SQL database
* Created structured relational tables
* Established relationships between customers, products, and transactions

### 5. SQL Analysis

Performed business queries to analyze:

* Revenue by gender
* High-value customers using discounts
* Top-rated products
* Shipping method impact on spending
* Subscription vs non-subscription behavior
* Discount-dependent product analysis
* Customer segmentation (New, Returning, Loyal)
* Revenue by age group
* Repeat purchase behavior

### 6. Dashboard Development (Power BI)

Built an interactive dashboard including:

* KPI cards
* Customer segmentation analysis
* Revenue and product insights
* Discount impact analysis
* Behavioral trend visualization

### 7. Reporting & Presentation

* Created detailed project report
* Built presentation using Gamma AI
* Summarized insights and business recommendations

---

## Dashboard Preview

(Add screenshot here)

```md
![Dashboard](images/dashboard.png)
```

---

## Results / Key Insights

* Subscription users contributed higher average spending.
* Discounts significantly influenced purchase behavior.
* Loyal customers generated consistent revenue contribution.
* Age group segmentation revealed high-value customer segments.
* Shipping preferences impacted spending patterns.
* Top-rated products strongly influenced repeat purchases.

---

## Business Recommendations

* Promote subscription programs to increase customer retention
* Build loyalty programs for repeat buyers
* Optimize discount strategies to balance profit and sales
* Focus marketing on high-value age groups
* Highlight top-rated and best-selling products in campaigns
* Improve customer targeting based on segmentation

---

## How to Run

### 1. Clone Repository

```bash
git clone <repository-link>
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Python Analysis

* Open Jupyter Notebook or Python scripts
* Execute EDA and cleaning steps

### 4. SQL Analysis

* Import dataset into MySQL Server
* Run SQL queries from `/SQL` folder

### 5. Power BI Dashboard

* Open `.pbix` file in Power BI Desktop

### 6. View Report & PPT

* Open report PDF and Gamma presentation

---

## Repository Structure

```plaintext
Customer-Shopping-Analysis/
│
├── Dataset/
├── Python/
├── SQL/
├── PowerBI/
├── Report/
├── Presentation/
├── Images/
└── README.md
```

---

## Author

**Jashwanth Varma**
Aspiring Data Analyst | Python | SQL | Power BI

