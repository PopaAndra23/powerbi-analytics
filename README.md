## 📌 Project Overview
The main goal was to take raw data from the AdventureWorks dataset, build a proper data model, and create an interactive dashboard in Power BI to analyze sales, products, and customer trends.

---

## 🛠️ What I Used & Applied
* **Tool:** Power BI Desktop
* **Data Modeling:** Star Schema (connecting Product, Customer, Territory, and Date tables to Sales facts)
* **Calculations:** Custom DAX measures (Total Revenue, Average Order Value, Year-over-Year Growth, YTD, MTD)
* **Security:** Row-Level Security (RLS) based on roles

* Dashboard Structure & Features

The project is divided into 4 main business areas, following the project requirements:

1. **Product Catalog Matrix (Ticket PBI-A01):** Analyzes the distribution and pricing of 296 finished goods. It highlights that *Bikes* dominate the high-price tier, while *Components* have the highest product count.
2. **Sales Overview (Ticket PBI-A02):** Tracks a total revenue of **$109.85M** across **31K unique orders** over a 4-year period (2011-2014).
3. **Customer & Regional Analytics (Ticket PBI-A03):** Explores customer purchasing patterns and maps sales by territory. *North America* ($79M) and specifically the *Southwest* region ($24.2M) are the top performers.
4. **Time-Intelligence (Ticket PBI-A04):** Measures growth trends over time, showing a strong overall YoY Growth of **+69.41%**.

---

## Main Business Insights
* **Product Dependency:** Over **86% of total revenue** comes exclusively from the *Bikes* category. To grow safely, the business should focus more on promoting *Accessories* and *Clothing*.
* **Regional Star:** The *Southwest* region is the main economic driver ($24.2M), meaning other territories have huge unexploited potential where successful strategies could be replicated.

---

## 🔧 Future Improvements (Feedback Integration)
 Here are the specific areas I am going to optimize in the next update

* **Better Time Filters (Slicers):** I will add a cleaner, dedicated time filter pane (Year/Month slicers) to make switching between different time frames much easier and more intuitive for the user.
* **Cleaner Visuals (UI/UX Layout):** Some charts are currently too crowded. I plan to simplify the layout, increase whitespace, and use conditional formatting or matrix tables to make the data easier to read at a glance.
