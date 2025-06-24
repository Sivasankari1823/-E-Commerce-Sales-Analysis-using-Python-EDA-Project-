# E-Commerce Sales Analysis using Python EDA-Project
## 🧠 About the Project

This project delivers a **comprehensive e-commerce analytics dashboard** that analyzes sales performance, customer behavior, and business KPIs. The goal is to extract actionable insights across product categories, regions, demographics, and time dimensions to support strategic decision-making.

## 🎯 Project Objective

To develop an **interactive business intelligence dashboard** using Python and Power BI that empowers stakeholders to:
- Monitor key performance indicators (KPIs)
- Identify business trends and seasonal patterns
- Improve inventory and return management
- Enable data-driven decision-making

| Question | KPI/Metric |
|----------|------------|
| 💰 What is the overall revenue generated? | **Total Sales** – $1.255M |

| 📦 Which categories generate the most sales? | **Category-wise Sales Distribution** |

| 🌍 How do regions perform against each other? | **Regional Sales Comparison** |

| 🔁 Which categories are returned the most? | **Return Rate % by Category** |

| 📅 Are there monthly/yearly patterns? | **Sales Trends over Time** |

| 👤 What are customers' purchase patterns? | **Avg Unit Price, Quantity per Customer** |

| 🚻 Are there gender-based differences? | **Avg Quantity by Gender** |

| 🚚 How efficient is our shipping process? | **Shipping Status Overview** |

## Dataset Used

- <a href="https://github.com/Sivasankari1823/-E-Commerce-Sales-Analysis-using-Python-EDA-Project-/commit/08a302df980d1e07d107dcedbf64a673ceffdbab"> Dataset</a>

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python (Pandas, Seaborn, Matplotlib) | Exploratory Data Analysis |
| Power BI | Dashboard and KPI Visualization |
| GitHub | Project hosting and version control |
| CSV | Raw data input  |
| Jupyter Notebook / Google Colab | Notebook execution and annotation |

## 📊 Project Deliverables

### 🔹 1. Python EDA Notebook

| 📂 EDA Area              | ✅ Tasks Completed                                                                 | 🛠️ Technologies / Tools Used            |
|--------------------------|-----------------------------------------------------------------------------------|-----------------------------------------|
| **Data Loading & Preprocessing** | ✅ Loaded CSV, used `.info()`, `.describe()`, `.head()` <br> ✅ Checked for missing values & duplicates <br> ✅ Extracted `year`, `month`, `month_name`, `weekday` | Python, Pandas |
| **Numerical Analysis**   | ✅ Distribution plots (histograms) <br> ✅ Boxplots for outliers <br> ✅ Skewness calculation <br> ✅ Descriptive statistics (`mean`, `median`, `std`) | Pandas, NumPy, Seaborn, Matplotlib |
| **Categorical Analysis** | ✅ Count plots for `gender`, `region`, `category`, `shipping_status`, `returned` | Seaborn, Pandas |
| **Cross Analysis**       | ✅ Total sales by region <br> ✅ Avg quantity by gender <br> ✅ Return rate (%) by category | Pandas, Seaborn |
| **Outlier Detection**    | ✅ Detected using IQR method for columns like `unit_price`, `shipping_fee` etc.  | Pandas, NumPy, Matplotlib |
| **Correlation Analysis** | ✅ Correlation matrix + heatmap for numerical columns                            | Pandas, Seaborn |
| **Time Series Analysis** | ✅ Extracted time features <br> ✅ Total sales by month (2024 & 2025) <br> ✅ Line chart comparison | Pandas, Matplotlib |

- <a href="https://github.com/Sivasankari1823/-E-Commerce-Sales-Analysis-using-Python-EDA-Project-/commit/528156f98434e17ae55eb2ca2dce42fc089e9314
"> EDA Project </a>


### 🔹 2. Power BI Dashboard
- Created dynamic KPIs (Sales, Quantity, Unit Price, Return Rate, Avg Age)
  
- Added slicers (Year, Month, Gender, Region, Category, Shipping Status)
  
-**Built multiple visualizations:**
  
  - Sales trend (2024 vs 2025)
    
  - Category-wise unit price
    
  - Return rate by category
    
  - Quantity by gender
    
  - Regional sales contribution

- <a href="https://github.com/Sivasankari1823/-E-Commerce-Sales-Analysis-using-Python-EDA-Project-/commit/2ec219c6e0ed7b9828251bd511a17f04074ee48a"> Dashboard </a>


- <a href="https://github.com/Sivasankari1823/-E-Commerce-Sales-Analysis-using-Python-EDA-Project-/commit/656c12833a0d24b09d0be4281b849e4021e12c1f"> Dashboard Screenshot 1</a>



- <a href="https://github.com/Sivasankari1823/-E-Commerce-Sales-Analysis-using-Python-EDA-Project-/commit/656c12833a0d24b09d0be4281b849e4021e12c1f"> Dashboard Screenshot 1</a>


### Sales Insights

**Overall Performance:**

The company achieved $1.255 million in total sales across 2,452 transactions, indicating strong business performance.

**Category Performance:**

•	Books lead with $331,730 (26.4% of total sales)

•	Clothing follows closely at $311,130 (24.8%)

•	Electronics at $309,915 (24.7%)

•	Home products at $303,730 (24.2%)

The sales distribution is remarkably balanced across all four categories, showing a well-diversified product portfolio.

**Regional Distribution:**

**Sales are evenly spread geographically:**

•	North: $330.45K (26.32%)

•	West: $316.2K (25.18%)

•	South: $307.23K (24.47%)

•	East: $301.63K (24.02%)

This balanced regional performance suggests effective nationwide market penetration.

### Customer Insights ###

**Gender Analysis:**

Average unit prices show no significant gender bias, with both male and female customers spending approximately $500 per unit on average. This indicates the product mix appeals equally to both demographics.

**Purchase Patterns:**

The data shows consistent customer engagement with an average of 4 items per transaction across the sample, suggesting customers are making substantial purchases rather than single-item buys.
Time Trends

**Year-over-Year Growth:**

•	2024: $669,125 in sales with 1,302 units sold

•	2025 (partial year): $586,380 with 1,150 units sold

The 2025 performance is tracking well considering it's only a partial year, suggesting sustained business momentum.

**Monthly Patterns:** 

The sales by month chart shows seasonal variations, with some months (particularly around month 10-12) showing stronger performance, likely indicating holiday shopping patterns.
Return Insights

### Return Rate Analysis ###

**Return rates vary significantly by category:**

•	Clothing: 11.6% (highest return rate)

•	Books: 11.0%

•	Home: 9.2%

•	Electronics: 9.1% (lowest return rate)

**Key Observations:**

•	Clothing's higher return rate (11.6%) is typical for fashion items due to fit and style preferences

•	Electronics have the lowest return rate (9.1%), indicating good product quality and customer satisfaction

•	The overall return rates are within acceptable e-commerce ranges (8-12%)

### Shipping Status Insights ###

While specific shipping status data isn't fully visible in the dashboard, the presence of this filter suggests the company tracks delivery performance. The customer data shows transactions spanning multiple quarters and months, indicating consistent order fulfillment throughout the year.

### Strategic Recommendations ###

1.	Inventory Management: Maintain balanced inventory across all categories given the even sales distribution

2.	Return Optimization: Focus on reducing clothing returns through better sizing guides and product descriptions

3.	Regional Strategy: Leverage the balanced regional performance to implement uniform marketing strategies

4.	Seasonal Planning: Prepare for peak months identified in the trend analysis

5.	Customer Retention: The consistent purchase quantities suggest good customer satisfaction - focus on loyalty programs to maintain this trend
The overall picture shows a healthy, well-balanced e-commerce business with strong performance across multiple dimensions.

## 🔍 Project Insights

| Insight | Detail |
|--------|--------|
| 📊 **Balanced Category Sales** | All 4 categories (Books, Clothing, Electronics, Home) ~25% each |
| 🧭 **Even Regional Performance** | < 3% sales difference between highest and lowest region |
| 🔁 **Clothing = Highest Returns** | 11.6% return rate (vs 9.1% in Electronics) |
| 🚻 **Gender Purchase Parity** | Avg unit price ~₹500 for both genders |
| 📈 **Sustained Sales YOY** | Strong year-over-year performance |
| 🕒 **Seasonal Peaks** | High sales in festive/holiday months |
| 🛒 **High Engagement** | Avg of 4 items per order → strong loyalty |


## 🧾 Final Conclusion

The e-commerce dashboard showcases a **robust business strategy** with  $1.255M in total sales and 2,452 transactions. The even distribution across categories and regions reflects a **well-diversified product mix** and **regional success**. Return rates are within industry norms, though **clothing returns** can be optimized. The **gender-neutral purchasing** and consistent customer behavior point to **broad market appeal**. 












