# Vendor-Performance-Analysis

## 📌 Overview  
This project analyzes **retail vendor performance, inventory turnover, and sales efficiency** using **SQL, Python, and Power BI**. The study highlights vendor-wise profitability, stock movement, and risk exposure, providing actionable strategies to optimize procurement and reduce cost.



## 🚀 Key Outcomes  
- Uncovered **$2.71M worth of unsold inventory** stuck in slow-moving vendor SKUs  
- Identified **65.7% supplier dependency**, exposing high concentration risk  
- Recommended diversification + bulk-buy strategy, leading to **72% projected cost savings**

## 🛠️ Tech Stack  
| Layer | Tools |
|-------|------|
| Data Storage | PostgreSQL |
| ETL / Queries | SQL (CTEs, Window Functions, Aggregations) |
| Analysis | Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn) |
| Visualization | Power BI |
| Testing | Hypothesis Testing (T-Tests, ANOVA) |



## 📌 Project Workflow  

### 🔹 1. Data Ingestion & ETL (PostgreSQL)
- Built scalable **CTE-based ETL pipelines**
- Executed **multi-table joins** for vendor-wise stock + revenue mapping  
- Reduced query execution time on large datasets via optimized indexed joins  

### 🔹 2. Python Analysis & Hypothesis Testing
- Calculated metrics: Inventory Turnover, Lead Time Efficiency, Profitability  
- Conducted:
  - **ANOVA** to compare vendor profitability groups  
  - **T-Test** to validate turnover differences between high vs low volume vendors  

### 🔹 3. Power BI Dashboard Highlights
📍 Key Metrics Displayed:
- **Unsold Stock Distribution**
- **Vendor Revenue vs Inventory Holding**
- **Supplier Dependency Risk**
- **Turnover & Return Benchmarking**

📌 Snapshot Deliverables:  
> *(Add Power BI visuals here once uploaded)*


## 📊 Metrics Computed
| Metric | Purpose |
|--------|---------|
| Inventory Turnover Ratio | Detect slow-moving SKUs |
| Vendor Profit Margin | Supplier-wise profitability |
| Sell-through Rate | Stock clearance efficiency |
| Dependency Index | Over-reliance risk |
| Holding Cost Estimation | Cost optimization measure |


## 💡 Insights & Business Recommendations
| Problem | Solution | Impact |
|---------|----------|--------|
| High supplier reliance (65.7%) | Diversify vendor portfolio | Risk reduction |
| High unsold stock ($2.71M) | Liquidation + reorder threshold tuning | Inventory clearance |
| High procurement cost | Bulk-buy strategy | **72% cost savings** |


## 📎 How to Run Locally

### 🔹 Clone the Repository
```bash
git clone https://github.com/Vasusai74/Vendor-Performance-Analysis.git
cd vendor-performance-analysis
