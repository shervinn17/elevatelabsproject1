# 🛍️ Retail Sales Performance & Profitability Analysis

## 📁 Project Overview
This project explores the **sales, profit, shipping behavior, and customer segments** for a retail business using **Python (Pandas, Seaborn, pandasql)** for backend data analysis and **Tableau** for visual storytelling. The objective is to uncover patterns that drive profitability, identify slow-moving inventory, and optimize operations for growth.

---

## 🧠 Key Insights

### 📊 Tableau Dashboard Insights

#### 1. **Sales Trends Over Time**
- Sales show an **upward trend** from 2014 to 2018.
- Order volumes are increasing alongside sales → growing customer base and/or product reach.

#### 2. **Shipping Method Impact**
- **Standard Class** accounts for the majority of sales.
- **Same Day shipping** has minimal sales, possibly due to higher costs or limited offering.
- Action: Optimize Standard Class operations to sustain performance and consider incentivizing Same Day where feasible.

#### 3. **Category Profitability**
- **Technology** and **Office Supplies** are the most profitable categories.
- **Furniture** lags in profit → possibly due to high cost or shipping complexity.

#### 4. **Customer Segment Analysis**
- **Consumers** make up the largest share (46.8%), followed by Corporate and Home Office.
- Suggests targeted promotions and retention strategies for the consumer segment could yield high returns.

#### 5. **Regional Performance**
- Strong profitability in coastal states (especially East Coast and West Coast).
- Southern and some central states show consistent losses → further investigation needed (e.g., shipping, pricing, demand).

#### 6. **Sales vs Profit Product Performance**
- **Phones, Chairs, and Copiers** yield high sales and profit.
- **Tables, Machines, Bookcases** show high sales but poor profit — potential margin leakage or return issues.
- **Art and Supplies** underperform in both sales and profitability → candidates for phasing out or reevaluation.

---

### 🐍 Python (Jupyter Notebook) Insights

#### 1. **Profit Margin by Sub-Category**
- Calculated `ProfitMargin = Profit / Sales`.
- Used SQL-like queries (`pandasql`) to rank sub-categories by average margin.
- Insight: Identify underperforming areas and prioritize margin improvement tactics.

#### 2. **Inventory Efficiency**
- Created `InventoryDays = Ship Date - Order Date` to simulate inventory turnaround.
- Weak correlation between inventory days and profit suggests limited profitability impact from shipping delays — but long delays should still be monitored.

#### 3. **Slow-Moving Inventory Detection**
- Defined thresholds:
  - High inventory days (75th percentile),
  - High quantity,
  - Low profit margin (<5%)
- Identified SKUs meeting all criteria.
- Action: Consider clearance, bundling, or improved marketing for these items.

---

## 📁 Files Included
- `Project 1 Elevate Labs.ipynb`: Python notebook with all backend data cleaning, querying, and visualization.
- `Tableau Dashboard Screenshot.png`: Visual dashboard summarizing retail KPIs.
- `Tableau Dashboard.twb`: Complete Interactive Dashboard
- `Report.pdf`: Summary Of the Entire Project 
- `README.md`: This file.

---

## 🚀 Recommendations
- Integrate slow-moving inventory and margin insights into **supply chain and marketing decisions**.
- Use **Tableau dashboards for executive-level monitoring**.
- Export product performance reports to inform **inventory planning and vendor negotiations**.

---

## 🔧 Tools Used
- Python: `pandas`, `numpy`, `seaborn`, `matplotlib`, `pandasql`
- Tableau: Interactive dashboards with filters for Region, Category, Ship Mode, Segment, etc.
- Excel: Source data for analysis

---

## 📬 Contact
For questions or collaboration, feel free to reach out!

