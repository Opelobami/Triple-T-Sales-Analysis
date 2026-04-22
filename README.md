# Triple-T-Sales-Analysis
A Power BI sales analytics solution for a multi-location retail chain identifying top and bottom performing products, category revenue contribution, regional sales gaps, and customer purchase patterns to support smarter inventory and commercial decisions.

---

## Project Overview
This project analyzes retail sales data for Tripple T, a multi-location retail chain operating across five major U.S. cities. The dataset covers transactions across five product categories; Clothing, Books, Electronics, Furniture, and Toys spanning the first half of 2023.
The analysis surfaces product performance, category contribution, regional sales patterns, and top customer purchasing behavior giving retail managers a clear picture of where revenue is concentrated and where commercial opportunities are being missed.
The final deliverable is a two-page interactive Excel dashboard filterable by month, category, and store location.

---

## Why This Project Matters
Every retail business collects sales data but very few use it to ask the right questions.
Tripple T operates across five cities with five product categories and thousands of customers. At nearly $5M in revenue, the business is not small. But without structured analysis and critical decisions, what to stock, where to invest, which customers to prioritize are made on instinct rather than evidence. This dashboard was built to change that from these perspectives.

- Which products are carrying the business, and which are quietly draining shelf space?
- Which store locations are outperforming, and which are leaving revenue on the table?
- Who are the highest-value customers, and what are they actually buying?

A honest note: This project was built at the early stage of my career as a data analyst as a data exercise before a clear business problem was defined. That is a common starting point for analysts learning the craft, and reflecting on it is part of what makes this portfolio entry worth reading. The insights and recommendations below show what the analysis should have been anchored to from the start

---

## Business Questions
1. How is total revenue trending across the first half of 2023?
2. Which products generate the most revenue and which generate the least?
3. Which product category is the strongest overall revenue contributor?
4. How does each category perform in both revenue and quantity sold?
5. Which store locations are driving the highest sales?
6. Who are the top 10 customers and what are they purchasing?
7. What is the average order value across the business?
8. Are there products that should be reconsidered or deprioritized based on sales performance?
   
---

## Dataset Summary
- Source: Sumit Mital Youtube Page
- Business: Triple T- multi-location retail chain
- Store Locations: Chicago, Houston, Los Angeles, Miami, New York
- Product Categories: Clothing, Books, Electronics, Furniture, Toys
- Period covered: January - June 2023
  
---

## Tools & Techniques  
- **Microsoft Excel**
  - Power Query for data cleaning and transformation  
  - Power Pivot for modeling and relationships  
  - Pivot Tables & Charts for analysis  
  - DAX & Calculated Columns for KPIs  
  - Interactive Dashboards for stakeholder visualization  

---

## Key Insights and Findings
- Revenue has been declining every month since January; roughly from $900K in January to under $800K by June. Over six months, that is a consistent downward trend that demands investigation before the second half of the year compounds the loss further.
- Clothing dominates both revenue and top products - Jeans ($227K) and Dress ($222K) lead all individual products, and Clothing leads all categories at $1.05M. The business's commercial identity is fundamentally a clothing business, regardless of how it is categorized.
- The bottom five products are all Furniture  Dresser, Monitor, Desk, Wardrobe, and Sofa collectively underperform every other category product. Furniture as a category also ranks last in total revenue at $951K despite having five products in the bottom-ten list.
- All five store locations perform within a surprisingly narrow revenue band. Los Angeles leads at $1.03M and Chicago trails at $953K, a gap of only $75K across five cities. This suggests either strong operational consistency or that no single location has yet found a meaningful growth lever.
- AOV sits at $496.30 with 10,000 orders from 10,000 customers — a 1:1 order-to-customer ratio suggests the dataset reflects one order per customer. If accurate, this means the business has no documented repeat purchasers; a significant retention gap worth investigating.

---

## Key Takeaways
- The revenue decline is the most urgent signal in the data. 6 consecutive months of decline is not seasonal noise. It is a trend that needs to be investigated.
- Clothing is the core business, and not by a small margin. Investment, inventory depth, and marketing attention should reflect that reality explicitly.
- Furniture is dragging category performance. Four of the five lowest-revenue products are Furniture items. The category either needs a strategic overhaul or a serious stock reduction.
- Regional performance parity masks individual opportunity. The narrow gap between cities means no location has broken out. That is either a ceiling or an untapped growth story waiting for the right push.
- The 1:1 order-to-customer ratio is either a data artifact or a retention crisis. Either way, it is worth resolving before drawing any conclusions about customer loyalty.

---

## Strategic Recommendations
- Diagnose the monthly revenue decline immediately. Cross-reference with external factors (seasonality, promotions, competitor activity) and internal ones (stock levels, pricing changes, staff). A six-month decline without an identified cause is a management risk.
- Double down on Clothing inventory and marketing. It leads in both revenue and top products. Expanding the range, improving display, or running targeted promotions in this category will move the needle faster than investing in underperforming ones.
- Review the Furniture category SKU by SKU. Sofa at $75K on a $496 AOV business is a poor performer. Reducing Furniture's floor space and inventory commitment in favour of Clothing or Books would likely improve both revenue and margin.
- Investigate Los Angeles and New York as growth test markets as the two highest-revenue locations, they are the natural candidates for piloting new product lines, promotional strategies, or loyalty programs before rolling out chain-wide.
- Build a customer retention and repeat purchase strategy. If every customer has only ordered once, the business is running entirely on acquisition. Even converting 10% of existing customers to a second purchase would meaningfully shift the revenue trajectory.

---

## Dashboard Visualization and Analysis walkthrough

[**View the data, modeling, calculations and dashboard screenshot here**](https://docs.google.com/spreadsheets/d/1C7b7F-p1C5zJqhZ2h22QJ7NPq8rH13Ub/edit?usp=drive_link&ouid=112288732127302670660&rtpof=true&sd=true)

---
## 🤝 Connect & Feedback
If you found this project useful or have suggestions, feel free to:

- ⭐ Star this repository
- 🐛 Open an issue for feedback or questions
- 🔗 Connect on LinkedIn — [Opeyemi Ayodeji](https://www.linkedin.com/in/opeyemi-ayodeji-86a696b0/)
