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


# YouTube Data Analysis Project

## Project Overview
This project focuses on analyzing YouTube channel and video data to uncover trends, performance drivers, and strategic insights. It combines Python-based data analysis with an interactive Tableau dashboard for dynamic visual exploration.

## Objectives
- Identify top-performing YouTube categories and creators.
- Understand the impact of sentiment on audience engagement.
- Analyze subscriber growth, earnings distribution, and content trends.
- Visualize insights using interactive dashboards.

## Tools Used
- **Python** (Jupyter Notebook)
  - Pandas, Numpy (Data manipulation)
  - Matplotlib, Seaborn (Visualization)
  - NLTK (Natural Language Processing for Sentiment Analysis)
- **SQL** (Pandasql library for SQL-like queries)
- **Tableau** (Dashboard building and visualization)

## Project Structure
```
├── Project 2 Elevate Labs.ipynb   # Python notebook with full data preparation, analysis, and EDA
├── Dashboard.twb / Dashboard.twbx # Tableau Dashboard files (if applicable)
├── README.md                      # Project documentation
├── Final Report.pdf               # 1-2 page project insights report
├── Dataset/                       # Raw YouTube data (CSV/Excel)
```

## Steps Involved

### 1. Data Preparation & Cleaning
- Loaded dataset and handled missing values.
- Standardized and formatted key fields (views, subscribers, likes, etc.).

### 2. Exploratory Data Analysis (EDA)
- Analyzed channel categories, view counts, and earnings patterns.
- Visualized trends and distributions using graphs.

### 3. Sentiment Analysis
- Performed sentiment analysis on video titles and tags using NLTK.
- Classified sentiments into Positive, Negative, or Neutral categories.

### 4. Key Insight Extraction
- Top YouTubers by views and subscribers.
- Categories with the highest audience engagement.
- Regional analysis of earnings.

### 5. Tableau Dashboard
- Created an interactive dashboard for:
  - Most Popular Genres
  - Top Subscribed Channels (Word Cloud)
  - Sentiment Trends Over Time
  - Revenue by Country
  - Category-Wise Subscriber Distribution

## Key Findings
- **Music** and **Entertainment** dominate YouTube in terms of views and subscribers.
- Positive and neutral sentiment titles tend to perform better.
- The U.S., India, and Brazil are leading markets for YouTube revenue generation.
- Top channels contribute disproportionately to overall views and earnings.

## Conclusion
This project provides valuable insights into YouTube’s performance landscape. Combining Python’s analytical capabilities with Tableau's visualization strengths results in actionable findings that can guide content creators, marketers, and strategists in optimizing their YouTube presence.

## Author
- **Project by:** Shervin Brett
- **Technologies:** Python, SQL, Tableau

