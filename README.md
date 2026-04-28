# yntra-E-commerce-Product-Analysis-Using-Excel
This project analyzes Myntra e-commerce product data using Microsoft Excel to uncover insights into pricing strategies, customer ratings, and brand performance. The analysis focuses on understanding how discounts influence customer engagement, how product ratings relate to popularity, and which brands and categories perform best. 

This project analyzes a Myntra product dataset to extract meaningful business insights through data cleaning, feature engineering, and visualization. The dataset includes product-level attributes such as pricing, ratings, and product links.

The main objective was to understand product performance, discount trends, and brand/category insights using analytical techniques.

⸻

📂 Dataset Features

Original Columns:

•⁠  ⁠Product Name
•⁠  ⁠Brand Name
•⁠  ⁠Rating
•⁠  ⁠Rating Count
•⁠  ⁠Marked Price
•⁠  ⁠Discounted Price
•⁠  ⁠Sizes
•⁠  ⁠Product Link

⸻

🧹 Data Cleaning & Transformation

Feature Extraction from Product Link:

New features were created by parsing product URLs:

•⁠  ⁠Product Category
•⁠  ⁠Brand Symbol
•⁠  ⁠Product Description
•⁠  ⁠Product ID

Data Cleaning Steps:

•⁠  ⁠Removed 2719 duplicate records using Product ID
•⁠  ⁠Ensured data consistency and uniqueness

⸻

⚙️ Feature Engineering

Two new analytical columns were created:

•⁠  ⁠Approx Revenue
    → Rating Count × Discounted Price
    (Used as a proxy to estimate product performance due to lack of direct sales data)
•⁠  ⁠Discount Percentage
    → Calculated from marked price and discounted price

⸻

📊 Data Analysis & Insights

🔻 Discount Analysis

•⁠  ⁠A pivot table was used to analyze discount vs performance
•⁠  ⁠Highest engagement observed in the 40%–60% discount range
•⁠  ⁠Indicates optimal pricing strategy for maximizing user interaction

⸻

🏆 Top Performing Brands

Top 10 brands identified based on estimated performance:

•⁠  ⁠Roadster ⭐ (Top Performer)
•⁠  ⁠Dressberry
•⁠  ⁠Plum
•⁠  ⁠And others

⸻

👕 Product Category Insights

Category-wise distribution showed:

•⁠  ⁠Perfume & Body Mist → 21% (Highest)
•⁠  ⁠T-Shirts → 16%
•⁠  ⁠Tops → 10%

👉 Conclusion: Lifestyle and personal care categories dominate platform engagement.

⸻

📊 Interactive Dashboard

An interactive dashboard was built using slicers to analyze:

•⁠  ⁠Brand performance
•⁠  ⁠Category-wise sales distribution
•⁠  ⁠Discount impact on product engagement

Dashboard Features:

•⁠  ⁠Dynamic filtering
•⁠  ⁠KPI tracking
•⁠  ⁠Brand-level analysis
•⁠  ⁠Category performance comparison

⸻

📸 Visualizations 
<img width="1440" height="900" alt="Screenshot 2026-04-28 at 1 34 05 am" src="https://github.com/user-attachments/assets/15bdc916-2635-4833-a0be-ff1835b3ab86" />
<img width="1440" height="900" alt="Screenshot 2026-04-28 at 1 34 05 am" src="https://github.com/user-attachments/assets/6c4adfca-a0ca-4abb-a37d-05150320d1f3" />
<img width="1440" height="900" alt="Screenshot 2026-04-28 at 1 47 42 am" src="https://github.com/user-attachments/assets/bc51f11a-712d-4c7a-bf8b-1957b21e5e8a" />
<img width="1440" height="900" alt="Screenshot 2026-04-28 at 1 25 33 am" src="https://github.com/user-attachments/assets/b0ed61aa-3d7d-46ff-aaeb-400833c4c172" />


•⁠  ⁠📊 Discount vs Sales Pivot Chart
•⁠  ⁠🏆 Top Brands Bar Chart
•⁠  ⁠📦 Category Distribution Pie/Bar Chart
•⁠  ⁠📈 Interactive Dashboard View

⸻

🚀 Key Skills Demonstrated

•⁠  ⁠Data Cleaning & Deduplication
•⁠  ⁠Web Data Feature Extraction
•⁠  ⁠Feature Engineering
•⁠  ⁠KPI Development
•⁠  ⁠Business Insight Generation
•⁠  ⁠Data Visualization & Dashboard Creation
•⁠  ⁠Analytical Thinking for Non-Sales Dataset

⸻

📌 Conclusion

This project demonstrates how structured analysis of product data can generate valuable business insights such as pricing strategy optimization, brand performance evaluation, and category demand understanding—even without direct sales data.
