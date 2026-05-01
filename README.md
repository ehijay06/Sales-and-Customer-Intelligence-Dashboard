# Sales-and-Customer-Intelligence-Dashboard
### OVERVIEW
This project presents an end-to-end Sales & Customer Intelligence Dashboard built in Power BI to analyze revenue performance, product profitability, customer behavior, and sales team effectiveness.
The goal of this analysis is to provide actionable insights that help organizations:

- Maximize revenue and profitability across product categories
- Identify top-performing products, customers, and sales employees
- Monitor revenue distribution across Nigerian cities
- Optimize sales targeting and exceed revenue targets

### OBJECTIVES

- Analyze revenue trends across months, cities, and customer segments
- Evaluate product category and subcategory profitability
- Assess sales employee performance against set targets
- Understand customer demographics and purchasing behavior
- Track key business KPIs including profit margin, return rate, and AOV

### KEY METRICS
The dashboard tracks the following metrics across four report pages:

- Total Revenue
- Profit & Profit Margin (%)
- Total Customers
- Total Orders
- Average Order Value (AOV)
- Return Rate (%)
- Sales Target vs. Achievement
- Revenue by Gender, Age Group, and City

### BUSINESS IMPACT
This dashboard enables sales and executive teams to:

- Pinpoint underperforming months and seasonal revenue dips
- Identify the highest-revenue product categories and top SKUs
- Reward and replicate behaviors of top-performing employees
- Tailor marketing strategies based on customer demographics and location
- Monitor whether revenue is tracking ahead or behind sales targets

Each KPI is supported with granular breakdowns to reveal the drivers behind headline numbers.

### KEY INSIGHTS

- Revenue: Total revenue reached ₦1.62bn against a sales target of ₦1.61bn, exceeding targets with a profit margin of 106.56%
- Seasonality: May recorded the highest monthly revenue at ₦158M, while November was the weakest at ₦91M — signaling a strong H1 and declining H2 trend
- Product Performance: Sports is the highest-revenue and highest-profit category at ₦0.34bn gross profit; Beauty is the lowest at ₦0.19bn
- Customers: The 36–45 age group drove the highest revenue at ₦0.43bn, with female customers accounting for 52.28% of total revenue
- City Distribution: Kano leads city-level revenue at ₦289M, closely followed by Lagos at ₦288M
- Sales Team: Employee 52 (E052) leads in total orders at 206; Employee 24 achieved the highest target achievement ratio at 1.37x
- Return Rate: A low return rate of 9% reflects strong product-market fit and customer satisfaction

### DATA MODEL
The dashboard is built on a structured data model connecting sales transactions to dimension tables:

- DIM_Product  |
- DIM_Customer |
- DIM_Employee | ───► FACT_Sales ◄── DIM_Date
- DIM_Location |
- DIM_Category |

### TOOLS AND TECHNOLOGIES USED

- Power BI — Data visualization and multi-page dashboard creation
- DAX (Data Analysis Expressions) — KPI calculations, target achievement ratios, and dynamic measures
- Microsoft Excel — Source data storage and preprocessing

## DASHBOARD PAGES
### 📊 Page 1 — Executive Overview
High-level KPIs and headline metrics for executive consumption:

- Revenue, Profit Margin, Total Customers, Total Orders, Return Rate
- Revenue by Month (bar chart)
- Revenue by Gender (donut chart)
- Revenue by City (Bing Map visual)

### 📊 Page 2 — Product Analysis
Deep-dive into category and product-level performance:

- Revenue and Profit KPI cards
- Average Order Value (AOV)
- Revenue by Category (bar chart)
- Cost and Profit by Category (stacked bar chart)
- Top 10 Products ranked by Gross Profit, Total Revenue, and Total Orders

### 📊 Page 3 — Customer Insights
Customer-centric view of purchasing behavior:

- Total Customers KPI
- Total Orders by Gender (donut chart)
- Revenue by Age Group (bar chart)
- Top 10 Customers by revenue (bar chart)
- Revenue by City (line chart across 6 cities)

### 📊 Page 4 — Sales Performance
Employee and sales target tracking:

- Revenue, Sales Target, and Profit KPI cards
- Sales by Employee — orders per sales rep (bar chart)
- Profit by Category (tile grid)
- Top Employees ranked by Total Revenue and Target Achievement ratio
# 
### DASHBOARD PREVIEW 
#
<img width="1462" height="1716" alt="photo_1_2026-05-02_00-45-37" src="https://github.com/user-attachments/assets/aded1164-9b26-472a-8e9f-1977340c359f" />

<img width="1468" height="1708" alt="photo_2_2026-05-02_00-45-37" src="https://github.com/user-attachments/assets/d169e085-6330-4afe-878c-59588628f290" />

### HOW TO USE
- Download the dataset and PBIX file from the project files below
- Open the .pbix file in Power BI Desktop
- Use slicers (Category, Subcategory, Location, Department) to filter and explore insights
- Navigate across the four report pages using the tab buttons at the top of each page

### PROJECT FILES

- Star Schema (CSV): [Download Dataset](https://github.com/ehijay06/Sales-and-Customer-Intelligence-Dashboard//blob/main/SalesInt)
- Dashboard: [Download PBIX](https://github.com/ehijay06/Sales-and-Customer-Intelligence-Dashboard//blob/main/SalesIntelligence.pbix)

## 👤 AUTHOR
### Nosa-Jeffery
Data Analyst | Power BI Developer

### Skilled in:
- Data Analysis (DAX, Excel, SQL)
- Data Visualization (Power BI)
- Dashboard Design & Storytelling
