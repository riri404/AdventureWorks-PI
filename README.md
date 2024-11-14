# AdventureWorks-PI
A business intelligence dashboard for the fictional AdventureWorks bike manufacturer, built in Microsoft Power BI.

# AdventureWorks Dashboard

![Dashboard Gif](https://github.com/riri404/AdventureWorks-PI/blob/main/Power%20Bi%20demonstration.gif)


## Introduction

The **AdventureWorks Dashboard** is a business intelligence project designed to provide valuable insights into the performance of a fictional cycling equipment company, *AdventureWorks*. Using **Power BI**, this dashboard offers an interactive, visually engaging way to analyze key business metrics and trends. This project demonstrates my ability to build insightful, data-driven reports that cater to various stakeholders, including executives, managers, and analysts.

The dataset used in this dashboard was provided by Maven Analytics as part of their **Power BI Desktop for Business Intelligence** course. The data is publicly available through Microsoft and includes key business areas such as product sales, revenue, customer performance, and more.

---
## Insights

The dashboard has revealed several key business insights that can guide strategic decision-making:

1. **Revenue & Profit**:
   - Between January 2020 and June 2022, **$24.9 million** in revenue was generated, resulting in a profit of **$10.5 million**.
   - **Accessories** drive the highest volume of orders, with **tires and tubes** being the most popular products. However, **bike sales** contribute the most significant portion of profit, accounting for around **92.3%** of total profits.

2. **Return Trends**:
   - **Clothing** has the highest return rate, with **shorts** being the most frequently returned item.
   - An outlier in the data shows the **Road - 750 Black, 48 bike** with an unusually high return rate of **4.23%**, suggesting a potential issue with the product that warrants further investigation (e.g., possible manufacturing defect).

3. **Geographic Insights**:
   - The majority of orders originate from the **United States**, but the **Australian market** stands out with over **6,000 orders**, almost matching the combined total from **Europe** (UK, Germany, and France), which is around **7,380 orders**.

4. **Customer Growth Trends**:
   - **Customer growth** was relatively flat from **January 2020 to July 2021**, but then experienced a dramatic spike of **350%**. This could be attributed to a strategic event, such as the opening of a new store location, rather than a temporary sales promotion.
   - Despite the increase in unique customers, **revenue per customer** has been declining steadily, likely due to factors such as inflation, higher post-COVID production costs, or supply chain issues.

---

## Key Features

- **Product-level Analysis**: Deep dive into product performance trends, helping users understand which products drive revenue, sales, and profit.
- **KPI Tracking**: Visualize and track key performance indicators (KPIs) such as revenue, sales, returns, and profit across different dimensions.
- **Regional Comparison**: Compare sales performance across different geographic regions to identify opportunities for expansion or optimization.
- **Targeted Audience Design**: Tailored dashboard pages for different stakeholders (e.g., executives, managers, analysts) to ensure data relevance and clarity.
- **Customer Segmentation**: Identify and analyze high-value customers to guide strategic marketing and sales initiatives.
- **AI-driven Insights**: Utilize Power BI’s AI capabilities, such as the Decomposition Tree and Anomaly Detection, to uncover hidden insights and reduce human error.
- **Executive-Ready Reporting**: Aesthetic and intuitive design, focused on providing a simple yet powerful analysis for high-level decision-making.

---

## Dashboard Design

### Connecting Data & Building Models

- **Data Import & Transformation**: The raw data was imported into Power BI, where it was cleaned, transformed, and structured using Power Query.
- **Relational Data Model**: Created a relational model that connects various data tables, ensuring accurate and efficient analysis.
- **DAX Measures**: Developed custom calculations and measures using DAX (Data Analysis Expressions) to track KPIs and perform complex aggregations.

### Interactive & Dynamic Dashboard Design

- Designed an interactive dashboard with drill-throughs, slicers, and filters to ensure users could easily navigate and access insights.
- Leveraged dynamic visualizations to allow for real-time updates and comprehensive analysis.

---

### Executive Summary View

The **Executive Summary View** provides a high-level snapshot of the company's overall performance, including:
- **KPI Tracking**: Visual indicators for revenue, profit, orders, and return rates.
- **Performance vs Targets**: A comparison of actual vs. target KPIs to assess business performance on a month-to-month basis.
- **Top Products**: Visuals highlighting top-performing products by category, making it easy for executives to focus on key revenue drivers.
- **Drill-through Navigation**: Users can click on specific products to navigate to detailed views for more granular analysis.

### Map View

The **Map View** visualizes total orders by geographic location, helping users quickly identify:
- **Regional Trends**: High-level sales patterns across various regions.
- **Filters by Region**: Slicer options for quick filtering by specific regions (e.g., North America, Europe, etc.).
- **Geographic Hotspots**: Areas where product demand is highest, enabling better allocation of resources and marketing focus.

### Product Detail View

The **Product Detail View** offers a detailed analysis of individual products:
- **Performance Metrics**: Displays trends for product-specific metrics such as orders, revenue, profit, returns, and return percentage.
- **Price Adjustment Analysis**: The ability to perform "what-if" analysis by adjusting pricing strategies and evaluating their potential impact.
- **Drill-through Data**: Provides in-depth analysis at the product level, helping decision-makers evaluate performance over time and across various metrics.

### Customer Detail View

The **Customer Detail View** allows users to analyze customer behavior at both the overall and per-customer levels:
- **Customer Segmentation**: Helps identify high-value customers and the contribution of each segment to overall revenue.
- **Customer Growth Trends**: Tracks customer acquisition patterns over time to understand periods of growth or stagnation.
- **Return Behavior**: Highlights customers with higher-than-average return rates, potentially flagging issues with product satisfaction.

---

## Custom Additions

To enhance the user experience and provide deeper insights, several custom features were added to the dashboard:
- **Custom Tooltips**: Interactive tooltips that provide on-demand, context-sensitive metrics when hovering over specific data points.
- **Popup Filter Pane**: A dynamic filter pane that allows users to quickly filter data by year or geographic location without disrupting the dashboard’s flow.
- **Sidebar Navigation**: Streamlined sidebar navigation that ensures users can easily switch between views, improving overall usability.

---






