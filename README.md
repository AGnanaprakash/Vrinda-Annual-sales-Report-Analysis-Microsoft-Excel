Vrinda Store Data Analysis (Excel Dashboard)
A complete Excel‑based data analysis project for Vrinda Store (2022): data cleaning, processing, analysis, and a final interactive dashboard/report. The project highlights sales trends, customer segments, channel performance, and geographic insights, with actionable recommendations.

🚀 Project Overview
Goal: Turn raw store transactions into insights and decisions by building a structured Excel workflow and dashboard:

Clean, standardize, and process transactional data.
Analyze orders, revenue, AOV, fulfillment outcomes, and seasonality.
Surface channel, state, category, gender, and age‑group performance.
Publish branded Word/PDF reports and charts.

Tools: Microsoft Excel (PivotTables, slicers, advanced formulas), Python (for chart exports & automated reporting)’

📂 Repository Structure
Plain Text.├─ data/│  └─ Vrinda Store Data Analysis complete project Excel Dashboard.xlsx├─ reports/│  ├─ Vrinda_Store_Data_Analysis_Summary.docx│  ├─ Vrinda_Store_Data_Analysis_Report.docx│  └─ (optional) Vrinda_Store_Branded_Report.pdf├─ charts/│  ├─ monthly_revenue.png│  ├─ monthly_orders.png│  ├─ gender_split.png│  ├─ agegroup_orders.png│  ├─ channel_revenue.png│  ├─ state_revenue.png│  └─ category_revenue.png└─ README.mdShow more lines

🧰 Data & Columns
From Vrinda Store sheet in the Excel file:

Order ID, Cust ID, Gender, Age, Age Group (Teenagers / Adult / Senior)
Date, Month, Status (Delivered / Cancelled / Returned / Refunded)
Channel (Amazon, Flipkart, Myntra, Ajio, Meesho, etc.)
SKU, Category, Size, Qty, Currency, Amount
Ship City, Ship State, Postal Code, Country


 Methodology


Data Cleaning

Remove duplicates, standardize text case, normalize status & gender (e.g., “women” → “Women”).
Parse dates and ensure Month consistency (e.g., Jan–Dec).
Coerce numeric fields (e.g., Amount, Qty) and handle nulls.



Data Processing

Compute derived metrics: Revenue (= Qty × Unit Price × (1−Discount) when applicable), AOV, outcomes rates.
Create helper columns: Month, Quarter, Year (if needed).



Analysis (Excel)

PivotTables: Revenue by Month, Channel, State, Category; Orders by Age Group.
Slicers for Region/State, Channel, Category, Month.
Charts for trends and segment distributions.

Reporting (Word/PDF)

Executive Summary, KPIs, visuals, insights, and recommendations.
Branded headings and clean layout for stakeholder sharing.




📈 Key Results (2022)

Total Revenue: ₹21,176,377; Total Orders: 31,047; AOV ≈ ₹682. [CodeInterpreter | PowerPoint]
Order Outcomes: Delivered 28,641 (~92.2%), Cancelled 844 (~2.7%), Returned 1,045 (~3.4%), Refunded 517 (~1.7%). [CodeInterpreter | PowerPoint]
Peak Month: March — Revenue ₹1,928,066; Orders 2,819. [CodeInterpreter | PowerPoint]
Gender Revenue: Women ₹13,562,773 (~64%) vs Men ₹7,613,604 (~36%). [CodeInterpreter | PowerPoint]
Top States (Revenue): Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu. [CodeInterpreter | PowerPoint]
Top Channels: Amazon leads; Flipkart & Myntra follow (per channel distribution pivot). [CodeInterpreter | PowerPoint]



💡 Insights

Women drive ~64% of revenue vs Men ~36%; marketing and assortment can reflect this skew.
Seasonality: A clear peak in March—align campaigns, inventory, and staffing to pre‑peak windows.
Channel concentration: Amazon dominates revenue—optimize listings, reviews, and sponsored placements there.
Geographic focus: Maharashtra, Karnataka, UP lead; tailor promotions & fulfillment SLAs for these states.
Category strategy: Double down on leading categories (visible in category mix), prune long‑tail SKUs.


✅ Recommendations

Targeted Campaigns: Prioritize top states/channels; pilot offers in underperforming regions.
Inventory Optimization: Keep high‑velocity SKUs closer to demand centers; rationalize slow movers monthly.
Pricing & Promotions: Use segmented discounts to protect margins; monitor AOV impact.
KPI Cadence: Track delivery/cancel/return/refund rates monthly; set thresholds and alerts in the dashboard.
Category Bundles: Create bundle promotions in leading categories to lift basket size and AOV.


🛠️ How to Reproduce (Excel)

Open data/Vrinda Store Data Analysis complete project Excel Dashboard.xlsx.
Review raw transaction sheet and PivotTable tabs.
Use slicers (Region/State, Channel, Category, Month) to interact with the dashboard.
Refresh pivots if the dataset changes (Data → Refresh All).
Export views to PDF/PNG for sharing
