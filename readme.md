





&#x20;\*\*README: McDonald’s Comprehensive Business Overview Dashboard\*\*



\## \*\*1. Project Overview\*\*



This project involved the end-to-end data analysis of McDonald’s sales performance. The primary objective was to transform raw transactional data into a dynamic, interactive dashboard that provides high-level business insights for executive decision-making.



\## \*\*2. The Dataset\*\*



The project utilized two core datasets:



\* \*\*Menu Master Table:\*\* Contains 32 unique menu items with detailed categories and pricing structures.

\* \*\*Transactional Data:\*\* A comprehensive log of 12,234 customer orders, including timestamps, order dates, and item IDs.



\## \*\*3. Analytical Workflow (Technical Methodology)\*\*



\### \*\*Phase 1: Data Integration \& ETL (Power Query)\*\*



To ensure a clean and structured dataset, the following ETL (Extract, Transform, Load) steps were performed:



\* \*\*Joins \& Relationships:\*\* Connected the Menu and Order tables using a \*\*Many-to-One relationship\*\* on the `Item ID` column.

\* \*\*Data Scrubbing:\*\* Executed \*\*Deduplication\*\* and handled missing values using the \*\*'Fill Down'\*\* logic to maintain data continuity.

\* \*\*Normalization:\*\* Ensured all price columns were formatted as currency and timestamps were standardized.



\### \*\*Phase 2: Feature Engineering\*\*



Custom dimensions were developed to unlock deeper insights:



\* \*\*Temporal Segments:\*\* Extracted \*Month Name\* and \*Day Name\* to track seasonal and weekly fluctuations.

\* \*\*Operational Buckets:\*\* Categorized orders into \*\*Meal Times\*\* (Morning, Lunch, Afternoon, Dinner) based on transaction timestamps.

\* \*\*Market Classification:\*\* Created a \*\*Weekday vs. Weekend\*\* classifier to analyze customer behavior patterns across the work week.



\## \*\*4. Dashboard Features\*\*



The \*\*"McDonald’s Comprehensive Business Overview"\*\* dashboard is built for interactivity and clarity:



\* \*\*Executive KPI Cards:\*\* High-level view of \*\*Total Revenue ($61k+)\*\*, \*\*Total Orders (12.2k)\*\*, and \*\*Average Order Value\*\*.

\* \*\*Peak Meal Time (Donut Chart):\*\* Visualizes that \*\*Lunch (49%)\*\* is the primary driver of sales volume.

\* \*\*Product Intelligence:\*\* Top 5 rankings for both \*\*Categories\*\* and \*\*Menu Items\*\* based on sales volume and revenue contribution.

\* \*\*Trends:\*\* A line chart representing the \*\*Monthly Sales Performance\*\* to identify peak demand months (January \& March).

\* \*\*Interactive Slicers:\*\* Dynamic filters for \*\*Meal Time\*\* and \*\*Day Name\*\* to allow real-time data drilling.



\## \*\*5. Key Business Recommendations\*\*



Based on the data-driven insights:



1\. \*\*Staff Optimization:\*\* Labor deployment should be maximized during the \*\*Lunch hours\*\* (the 49% peak window).

2\. \*\*Marketing:\*\* Targeted family-oriented promotions are recommended for \*\*Weekends\*\* to bridge the revenue gap compared to Weekdays.

3\. \*\*Menu Strategy:\*\* Capitalize on the high volume of \*\*Side Salads\*\* by introducing healthy-choice meal combos.



\---



\### \*\*6. Technical Stack\*\*



\* \*\*Microsoft Excel:\*\* Core Analytical Engine.

\* \*\*Power Query:\*\* Data Cleaning and Transformation.

\* \*\*Pivot Modeling:\*\* Advanced Data Aggregation.



\---





