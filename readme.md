**🍔 McDonald's Comprehensive Business Overview Dashboard**

An interactive business intelligence dashboard designed to transform
raw McDonald's transactional data into clear, executive-level insights
for decision-making.

**📌 Project Overview**

This project involved the end-to-end analysis of McDonald's sales
performance, from raw transactional data preparation to the creation
of a dynamic and interactive business dashboard.

The primary objective was to transform raw sales data into meaningful
insights covering:

💰 Revenue performance

🧾 Order volume

🍽️ Meal-time performance

📦 Product and category performance

📅 Monthly sales trends

🗓️ Weekday vs. weekend behavior

The final dashboard provides a high-level yet interactive view of
business performance, helping decision-makers identify demand patterns
and opportunities for operational improvement.

**📂 1. Dataset**

The project utilized two core datasets:

1.🍟 Menu Master Table

Contains 32 unique menu items with detailed information about:

Menu items

Categories

Pricing structures

🧾 Transactional Data

Contains a comprehensive record of 12,234 customer orders,
including:

Timestamps

Order dates

IteM IDs

⚙️ 2. Analytical Workflow

Phase 1 --- Data Integration & ETL

Data preparation and transformation were performed using Power
Query.

🔗 Joins & Relationships

Connected the Menu Master and Order tables.

Established a Many-to-One relationship using the Item ID
column.

🧹 Data Scrubbing

Performed deduplication to remove duplicate records.

Handled missing values using Fill Down logic.

Maintained data continuity throughout the transformation process.

💲 Data Normalization

Standardized price columns using currency formatting.

Standardized timestamp formats for consistent analysis.

Phase 2 --- Feature Engineering

Additional analytical dimensions were created to enable deeper business
analysis.

🕒 Temporal Segmentation

Extracted:

Month Name

Day Name

These dimensions were used to analyze seasonal and weekly fluctuations
in customer demand.

🍽️ Operational Buckets

Transactions were categorized into four Meal Times based on
transaction timestamps:

🌅 Morning

🍴 Lunch

☕ Afternoon

🌙 Dinner

📅 Market Classification

Created a Weekday vs. Weekend classification to analyze differences
in customer behavior throughout the week.

📊 3. Dashboard Features

The McDonald's Comprehensive Business Overview dashboard was
designed with a focus on interactivity, clarity, and executive-level
reporting.

💳 Executive KPI Cards

Provides an immediate overview of:

KPI                                       Performance

💰 Total Revenue                           $61k+
🧾 Total Orders                             12.2k
💵 Average Order Value     Available in dashboard

🍩 Peak Meal Time Analysis

A Donut Chart highlights the contribution of different meal periods.

Key insight:
🍴 Lunch accounts for 49% of sales volume, making it the primary
driver of sales activity.

🏆 Product Intelligence

The dashboard provides Top 5 rankings for:

Product Categories

Menu Items

These rankings highlight the products and categories contributing most
strongly to sales volume and revenue.

📈 Monthly Sales Trends

A Line Chart tracks monthly sales performance and helps identify
periods of higher demand.

Peak demand months identified:

🥇 January

🥈 March

🎛️ Interactive Slicers

Users can dynamically filter the dashboard using:

Meal Time

Day Name

This enables real-time exploration and drilling into specific customer
behavior patterns.

💡 4. Key Business Recommendations

The analysis produced the following data-driven recommendations:

1. 👥 Staff Optimization

Labor deployment should be maximized during lunch hours, which
represent the 49% peak window identified in the analysis.

Business impact:
Better staffing alignment during peak demand can support smoother
operations during the busiest period.

2. 📣 Weekend Marketing Strategy

Targeted family-oriented promotions are recommended for weekends to
help bridge the revenue gap compared with weekdays.

Business impact:
Weekend-focused campaigns can be used to strengthen customer engagement
during comparatively weaker periods.

3. 🥗 Menu Strategy

Capitalize on the high sales volume of Side Salads by introducing
healthy-choice meal combos.

Business impact:
Combining a high-volume item with meal offerings can create an
opportunity to strengthen the healthy-choice segment.

🛠️ 5. Technical Stack

Technology                          Purpose

📊 Microsoft Excel              Core analytical engine

🔄 Power Query                  Data cleaning and transformation

📌 Pivot Modeling               Advanced data aggregation

🔄 6. Project Workflow

Raw Transactional Data
        ↓
Data Cleaning & Deduplication
        ↓
Power Query Transformation
        ↓
Menu + Transaction Data Integration
        ↓
Feature Engineering
        ↓
Pivot Modeling & Aggregation
        ↓
KPI & Chart Development
        ↓
Interactive Dashboard
        ↓
Business Insights & Recommendations

🎯 7. Project Highlights

What this project demonstrates

✅ End-to-end data analysis workflow

✅ Data cleaning and transformation

✅ Table relationships and data integration

✅ Feature engineering

✅ Business-focused KPI development

✅ Interactive data visualization

✅ Trend analysis

✅ Customer behavior analysis

✅ Data-driven business recommendations

📁 8. Suggested Repository Structure

McDonalds-Business-Overview-Dashboard/
│
├── 📊 McDonalds_Dashboard.xlsx
├── 📄 README.md
└── 📁 Data/
    ├── Menu_Master.csv
    └── Transactional_Data.csv

Note: Update the filenames above to match the actual files
included in your GitHub repository.

👩‍💻 9. Author

Project: McDonald's Comprehensive Business Overview Dashboard

Focus: Business Analytics & Data Visualization

⭐ Conclusion

This project demonstrates how raw transactional data can be transformed
into an interactive, business-focused dashboard that communicates
key performance indicators, customer demand patterns, product
performance, and actionable recommendations.

The combination of Excel, Power Query, Pivot Modeling, and interactive
visualization creates a practical analytical solution for
executive-level business reporting.

🍔 From Raw Data → Insights → Decisions







