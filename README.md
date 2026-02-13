# Beyond-the-Numbers-Unlocking-Sales-Performance-in-Nigeria
A Data-Driven Analysis of Retail Trends in Lagos, Abuja, and Kano
**📖 Project Overview**
This project presents a detailed analysis of sales transactions recorded between January 2, 2024, and March 1, 2024. The dataset covers 100 unique transactions across four major Nigerian regions: Lagos, Abuja, Kano, and Ibadan.
The analysis focuses on two primary product categories: Technology and Grocery, managed by a sales team of five representatives. The goal was to move beyond basic reporting to uncover actionable insights regarding regional demand, high-value clients, and sales efficiency.
**🎯 Objectives**
The primary objectives of this analysis were to:
•	Evaluate Revenue & Volume: Assess total revenue generation and sales volume across different categories.
•	Regional Analysis: Identify high-growth markets and regional performance disparities.
•	Performance Tracking: Assess individual sales representative performance to identify top talent.
•	Trend Identification: Analyze product demand trends (Tech vs. Grocery).
•	Strategic Recommendations: Provide data-driven recommendations to optimize future sales strategies.
**🛠️ Technical Methodology**
To derive these insights, the analysis was conducted entirely in Microsoft Excel, focusing on data integrity, dynamic aggregation, and advanced formulas.
1. Data Transformation & Feature Engineering
Before analyzing raw figures, the dataset was enriched to allow for granular analysis:
•	Temporal Analysis: Utilized TEXT and WEEKNUM functions to extract month and week numbers, enabling the identification of weekly sales trends.
•	Logical Segmentation: Applied Conditional Logic (Nested IF) to create binary flags for high-ticket orders (exceeding ₦50k and ₦100k).
2. Statistical Aggregation
Avoided manual filtering in favour of dynamic functions for scalability:
•	SUMIFS & COUNTIFS: Primary drivers for regional and category-based reports (e.g., calculating Total Sales specifically for 'Tech' in 'Lagos').
•	AVERAGEIF: Used to determine Average Order Value (AOV) per Sales Rep and Region.
3. Advanced Data Retrieval & Validation
Ensured transactional accuracy using lookup and reference techniques:
•	Lookup Functions (XLOOKUP, INDEX & MATCH): Retrieved specific transactional data (e.g., finding specific sales amounts by OrderID) and validated product categories.
•	Data Validation: Checked for duplicates using OrderID as the primary key to ensure unique revenue reporting.
**🔍 Key Findings** 
💰 Revenue & Sales Snapshot
Metric	Value
Lagos Total Sales	₦4,326,860
Tech Category Revenue	₦9,889,668
Top Rep Revenue (Samuel)	₦5,564,991
Avg. Order Value (>₦100k)	₦218,327
**📈 Segment Insights**
•	Top Performing Region: Lagos (Highest Revenue)
•	Top Category: Technology (Revenue Driver) vs. Grocery (Volume Driver)
•	Top Sales Rep: Samuel (Revenue) & Grace (Efficiency/AOV)
•	First Product Sold in 2024: Mouse
**📉 Detailed Analysis**
1. Category Performance: Tech vs. Grocery
The product portfolio is distinctively split:
•	Technology: The primary revenue driver. High-ticket items (Laptops, Monitors, Phones) contributed approximately ₦9.8M to the total revenue.
•	Grocery: The volume driver. While unit prices are lower, the order frequency is significant, with an average transaction value of ₦150,500.
2. Regional Performance
•	Lagos: The clear market leader, generating ₦4.3M. This indicates high purchasing power and strong market penetration.
•	Abuja: Shows strong performance specifically in the Tech category.
•	Kano & Ibadan: Consistent order flow, primarily driving the Grocery segment.
3. Sales Representative Analysis
•	Samuel: The top revenue generator (₦5.5M total revenue).
•	Grace: Highest efficiency, with an average sale per transaction of ₦146,013, indicating success in closing bulk or premium deals.
•	Aisha: High activity level (20 orders handled), driving volume but with a lower average order value.
**🚀 Strategic Recommendations**
Based on the data, the following strategies are recommended for Q2 2024:
1.	Inventory Optimisation:
o	Prioritise stock levels for high-velocity Tech items (Mice, Keyboards, Phones) in Lagos and Abuja warehouses to prevent stockouts during peak demand.
2.	Sales Training & Knowledge Sharing:
o	Organise sessions where top performers (Samuel and Grace) share conversion strategies to help the rest of the team increase their Average Order Value (AOV).
3.	Targeted Regional Strategy:
o	Lagos: Maintain aggressive marketing; it is the "Cash Cow."
o	Kano/Ibadan: Introduce "Tech + Grocery" bundle offers (e.g., Office Packs) to increase transaction value in these lower-AOV regions.
o	Corporate B2B: Create bulk grocery packages for corporate clients to push the grocery average sale above the current ~₦150k baseline.

