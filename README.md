**Puma India Footwear: Pricing and Product Mix Dashboard

An end-to-end analysis of 1,533 Puma India footwear listings using Excel, SQL (PostgreSQL) and Power BI: from cleaning messy catalog data to answering five business questions in an interactive dashboard.

Dashboard

**Project overview**

Goal: understand how the catalog is priced and mixed across product types, genders and price segments.

Dataset: Puma India footwear product listings (2,055 raw rows, 1,533 after cleaning). Columns include product name, category, colours, price, sizes and product code. Source: [add the link to your dataset here].

Average price: ₹4,558 | Median price: ₹3,499 | Product types: 9
**Tools and workflow**
Step	Tool	What I did
1. Cleaning	Excel	Removed duplicates and blank rows, converted price to numbers, created Product Type and Price Segment columns, explored with pivot tables
2. Analysis	SQL (PostgreSQL)	Loaded the cleaned data and wrote queries (aggregations, window functions, correlation) to answer the five business questions and verify the numbers
3. Visualisation	Power BI	Built an interactive dashboard with KPI cards, charts, slicers and DAX measures
   
**Dashboard features**
KPI cards: average price, total products, product types, highest price
Charts: price distribution, men vs women vs unisex split, price segment share
Tables: top product types and top products by price
Slicers: filter the whole page by Product Type and Gender

**Key findings**
Sneakers (29.7%) and Running (26.0%) make up 55.8% of the catalog.
Running shoes average ₹6,782, well above the ₹4,558 catalog average, and 9 of the 10 most expensive products are Running shoes from the NITRO range.
Mid-range (₹2,500 to ₹5,000) is the largest price segment at 42.1%.
Men's products have the highest average price (₹5,091), but the typical women's product costs more (median ₹3,844 against ₹3,299).
The number of colours has almost no link to price (correlation 0.01).


