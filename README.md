# Cadence-Co.-Dashboard
## 1. 🛞 Cadence Co.: Global Bicycle Manufacturer Insights Dashboard
An end-to-end, dynamic Power BI analytics solution designed to track manufacturing key performance indicators (KPIs), analyze product trends, monitor regional market performance across global territories, and segment high-value customer behavior from January 2020 through June 2022.

## 2. Short Description / Purpose
The Cadence Co. Dashboard is a comprehensive, four-page interactive reporting solution created for executive leaders and operational decision-makers at Cadence. Built from raw transactional datasets, it translates complex sales, returns, customer, and product data into actionable insights, enabling the team to monitor financial performance, optimize product offerings, evaluate regional markets, and refine targeted customer marketing strategies.

## 3. Tech Stack
The dashboard was built using the following tools and technologies:

•  📊 Power BI Desktop – Core data visualization platform used for dashboard architecture, page navigation, and report layout.<br>
•  📂 Power Query – ETL (Extract, Transform, Load) engine used for data cleaning, type formatting, unpivoting, merging, and shaping raw CSV files.<br>
•  🧠 DAX (Data Analysis Expressions) – Applied for dynamic metrics, time-intelligence calculations (e.g., Previous Month comparison), dynamic visual switches, target gauges, and custom pricing scenarios.<br>
•  📝 Data Modeling – Star-schema relational model built by connecting Fact tables (Sales Data, Returns Data) to Dimension tables (Customer, Product, Product Category, Product Subcategory, Territory, Calendar).<br>
•  📁 File Format – .pbix for report design and interactive modeling, .csv for source files, and .png for dashboard documentation.<br>

## 4. Data Source
Source: mavenanalytics.io & Bing Maps

Raw CSV files containing historical operations of Cadence Co. from January 2020 to June 2022 including details on its customers, products, sales and returns.

## 5. Features / Highlights
### •  Business Problem :-

As a fast-growing global cycling equipment manufacturer, Cadence Co. previously lacked a unified reporting platform. Data was trapped in siloed transactional CSV files, making it difficult for management to assess overall business health, identify high-return product lines, compare performance across global sales territories, or understand customer purchasing power.

### • Goal of the Dashboard :-

To deliver a multi-page interactive dashboard that:<br>
  - Aggregates sales, cost, profit, and return metrics into executive-level KPIs.<br>
  - Enables deep-dive analysis on individual product performance and pricing sensitivity.<br>
  - Provides dynamic geographical mapping of sales volume across global territories.<br>
  - Segments customer trends by income, occupation, and lifetime value to identify key demographic drivers.

### • Walkthrough of Key Visuals :-
#### 1. Executive Level Report (Page 1)
- Top KPI Cards: Instant high-level performance metrics showcasing $24.9M Revenue, $10.5M Profit, 25.2K Orders, and a 2.2% Return Rate.
- Revenue Trending Line Chart: Multi-year trend analysis showing exponential revenue growth from early 2020 through mid-2022 alongside a projected trend line.
- Monthly Performance Cards: Highlights recent performance ($1.83M Monthly Revenue, 2,146 Monthly Orders, 166 Monthly Returns) with month-over-month percentage changes.
- Orders by Category (Horizontal Bar Chart): Visual comparison of category order volumes (Accessories: 17.0K, Bikes: 13.9K, Clothing: 7.0K).
- Top 10 Products Table: Detailed breakdown showing individual orders, revenue, and conditional formatting enabled return percentages.
- High-Impact Callout Cards: Quick highlights pinpointing the Most Ordered Product Type (Tires and Tubes) and Most Returned Product Type (Shorts).

#### 2. Product Detail Report (Page 2)
- Selected Product & Target Gauges: Dynamic visual showing the currently selected product using drill-through option in the Exec Dashboard paired with gauge visuals tracking Monthly Orders vs. Target (213 / 234), Revenue vs. Target ($1,668 / $1,804), and Profit vs. Target ($1,044 / $1,129).
- Price Adjustment What-If Slider: Dynamic pricing simulator allowing management to adjust price percentages (e.g., +10%) and visually compare Total Profit vs. Adjusted Profit over time.
- Product Metric Selection (Radio Slicer & Area Chart): Toggle option letting users dynamically switch the bottom area chart visual between Orders, Revenue, Profit, Returns, and Return %.

#### 3. Map Report (Page 3)
- Global Regional Slicers: Top button bar allowing single-click filtering by continent (Europe, North America, Pacific, or Select All).
- Dark-Themed Interactive World Map: Geographical bubble map displaying order density across key markets including the United States, Canada, United Kingdom, Germany, France, and Australia.

#### 4. Customer Detail Report (Page 4)
- Customer Summary KPIs: Highlights 17.4K Unique Customers and an average $1,431 Revenue per Customer.
- Total Customers Line Chart: Monthly growth tracking of unique customer acquisition over time.
- Demographic Donut Charts: Breakdowns analyzing order distribution by Income Level (Average: 11.6K, Low: 10.3K, High: 2.8K) and Occupation (Professional: 7.9K, Skilled Manual: 6.0K, Management: 4.4K).
- Top 100 Customers Matrix: Searchable leader table listing top individual buyers ranked by orders and total spend.
- Top Customer Highlight Card: Dynamic Visual callout featuring the top revenue generator along with their orders and revenue.
- Text Insight: An interactive business insight regarding a specific customer demographic. All visuals update upon clicking the insight, providing additional context to it

### • Business Impact & Insights :-
- Product Portfolio Optimization: Identified that while Accessories generate the highest order volume, high-margin Bikes drive overall profitability. Highlighting Shorts as the most returned item allows quality assurance teams to investigate potential sizing or material issues.
- Strategic Pricing & What-If Planning: The product detail price slider gives product managers the ability to model revenue and profit impacts before implementing price changes.
- Territory Expansion: Geographic map visuals clearly illustrate strong market penetration in North America while pointing to growth opportunities across European and Pacific regions.
- Targeted Marketing & Loyalty Programs: Customer demographic breakdowns reveal that Professional and Skilled Manual income brackets generate the highest order volume, guiding future ad campaigns toward those specific buyer personas.

## 6. Screenshots / Demos
![Dashboard Preview](https://github.com/UtkarshChandra63/Cadence-Co.-Dashboard/blob/main/Snapshots%20of%20the%20Dashboard/01-Snapshot%20of%20Executive%20Level%20Report.png)
