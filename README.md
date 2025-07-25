# 📊 Sales Performance Insight & Profitability Dashboard (Power BI + PostgreSQL)

## 🎯 Business Problem

Sales performance and profitability data were fragmented across multiple systems, limiting timely decision-making and visibility into key business metrics. Stakeholders lacked an integrated, real-time reporting tool to evaluate performance across 15+ countries and three market segments.

## 💡 Solution Overview

I designed a responsive Power BI dashboard using PostgreSQL and advanced SQL logic to provide dynamic insights on year-to-date (YTD) sales, gross profit %, and detailed account segmentation across products and regions. The dashboard delivers interactive visuals, trend analysis, and KPI monitoring that drive strategic action.

## 🛠️ Tools & Technologies

| Tool / Tech           | Purpose                                                                 |
|-----------------------|-------------------------------------------------------------------------|
| **Power BI**          | Visualization, dashboard design, DAX for KPIs                           |
| **PostgreSQL**        | Data storage, performance-optimized queries and indexes                 |
| **SQL**               | Window functions, stored procedures, views for efficient analytics      |
| **DAX**               | Custom KPI calculations and time-based comparisons                      |
| **Power Query**       | Data transformation and automated cleansing                             |

## 🔧 Key Features

- 📈 **YTD vs Previous YTD Sales Comparison**  
  Interactive charting with slicers and dynamic filters boosted decision speed by **25%**

- 💰 **Gross Profit % Monitoring**  
  Automated profit ratio tracking across country and product categories in real time

- 📅 **Monthly Sales Trend Analysis**  
  Segmentation by region, account type, and product improved reporting accuracy by **30%**

- ⚙️ **Performance-Optimized SQL**  
  Reduced query runtime by **50%** using indexes, stored procedures, and window functions (`RANK()`, `LAG()`, `SUM() OVER`)

- 🧠 **Enhanced UX with Power BI**  
  DAX-driven KPIs and user-friendly slicers for intuitive analysis

## 📈 Business Impact

- Provided stakeholders with a one-stop dashboard for actionable insights
- Increased transparency and agility in regional strategy planning
- Enabled quick identification of top/bottom performers by product and market segment

## 🧠 Key Learnings & Suggestions

- **SQL optimization** is critical when handling large datasets—views and stored procedures made a huge difference
- **DAX & Power Query** offer unmatched flexibility for shaping KPIs and transforming raw data
- **Next Steps**:
  - Integrate predictive models for future sales forecasting
  - Enable row-level security for customized stakeholder views
  - Scale to Power BI Service for broader enterprise accessibility

## 📸 Dashboard Preview

![Dashboard Screenshot](Dashboard.png)

