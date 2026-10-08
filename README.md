# POWERBI-Project-Malven-Project
This project guides you through building an end-to-end Power BI report for Maven Market, a multi-national grocery chain in Canada, Mexico, and the United States
This project guides you through building an end-to-end Power BI report for Maven Market, a multi-national grocery chain in Canada, Mexico, and the United States, following a four-part workflow:

Part 1: Connecting & Shaping Data — Import CSV files including Customers, Products, Stores, Regions, Calendar, Return_Data, and 1997–1998 transaction records. Tasks include merging fields (e.g., full_name, full_address), extracting values like birth_year and area_code, adding conditional logic (has_children), replacing null values, and formatting data types.

Part 2: Creating the Relational Model — Build a star/snowflake schema placing lookup tables above data tables (Transaction_Data and Return_Data). Connect tables using 1-to-many, single-direction relationships with primary and foreign keys. Categorize geographic fields, format dates to M/d/yyyy, and hide foreign key fields from the report view to clean up the data panel.

Part 3: Adding DAX Columns & Measures — Create calculated columns such as Weekend, End of Month, Current Age, Priority, and Price_Tier. Write key DAX measures for business metrics, including:

Volume & Counts: Quantity Sold, Quantity Returned, Total Transactions, Total Returns, and Unique Products.

Financials: Total Revenue, Total Cost, Total Profit, Profit Margin, and Return Rate.

Time Intelligence & Targets: YTD Revenue, 60-Day Revenue, prior month metrics (Last Month Revenue, Last Month Profit), and a dynamic Revenue Target (+5% over the previous month).

Part 4: Building the Report — Design an interactive "Topline Performance" dashboard featuring:

A Matrix showing the top 30 brands with data bars and color scales.

KPI Cards tracking monthly transactions, profit, and returns against targets.

A Map and Treemap for geographic drill-downs by country, state, and city.

A Column Chart for 1998 weekly revenue trends and a Gauge Chart for target tracking.

Interactive features like bookmarks (e.g., "Portland 1000 Sales") linked to a dedicated Notes page.
