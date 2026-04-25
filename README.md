# BlinkIT_grocery_dashboard

## 1. 🏷️ Project Headline

**BlinkIT Grocery Sales Dashboard – Retail Performance & Outlet Analytics**


## 2. 📋 Purpose

This dashboard provides an end-to-end sales analytics solution for BlinkIT's grocery operations across **8,523 product-outlet records** and **10 store outlets** established between 2011–2022. It enables retail managers and business analysts to track total revenue, evaluate product category performance, compare outlet types and sizes, analyse city-tier-wise sales distribution, and monitor customer ratings — helping stakeholders make smarter inventory, expansion, and merchandising decisions.


## 3. 🛠️ Key Technologies Used

- **Microsoft Power BI Desktop** — interactive dashboard and visual analytics (`.pbix`)
- **Microsoft Excel** — primary data source and raw data staging (`.xlsx`)
- **DAX (Data Analysis Expressions)** — calculated KPIs such as total sales, average sales, average rating, and item count measures
- **Power Query (M Language)** — data cleaning (standardising fat content labels: `LF → Low Fat`, `reg → Regular`), type conversion, and transformation inside Power BI


## 4. 📦 Data Source

**More info on where data come from and how it's structured.**
- **Source: Kaggle.**
- **File:** `BlinkIT_Grocery_Data.xlsx`
- **Records:** 8,523 rows across 10 outlets
- **Fields (12 columns):**

| Field | Details |
|---|---|
| `Item Identifier` | 1,559 unique product SKUs |
| `Item Type` | 16 categories (Fruits & Vegetables, Snack Foods, Household, Frozen Foods, Dairy, Canned, Baking Goods, etc.) |
| `Item Fat Content` | Low Fat / Regular (with raw variants needing cleaning) |
| `Item Weight` | Product weight in kg |
| `Item Visibility` | Shelf visibility score (0–1) |
| `Outlet Identifier` | 10 unique store outlets (OUT010–OUT049) |
| `Outlet Establishment Year` | 2011 to 2022 |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 cities |
| `Outlet Type` | Grocery Store, Supermarket Type 1/2/3 |
| `Sales` | Item-level sales revenue (₹31 – ₹267) |
| `Rating` | Customer rating (up to 5.0; avg ~3.97) |


## 5. ✨ Features of the Dashboard

- **Top-Line KPIs** — Total sales (₹1.20M), number of items (1,559), average sales per item (₹141), and average customer rating (3.97) displayed as headline cards
- **Sales by Item Type** — Bar/column chart ranking all 16 product categories; Fruits & Vegetables (₹178K) and Snack Foods (₹175K) lead the pack
- **Fat Content Analysis** — Donut/pie split of Low Fat vs. Regular items by sales volume — useful for health-conscious product strategy
- **Outlet Type Performance** — Supermarket Type 1 dominates with ₹787K in sales vs. Grocery Stores at ₹152K — clear tier comparison
- **Outlet Size Breakdown** — Medium-sized outlets generate the highest revenue (₹508K), followed by Small (₹445K) and High (₹249K)
- **City Tier Analysis** — Tier 3 cities outperform with ₹472K in sales vs. Tier 1 (₹336K), revealing strong small-city demand
- **Outlet Establishment Year Trend** — Line/area chart showing how sales correlate with outlet age and expansion history (2011–2022)
- **Item Visibility vs. Sales** — Scatter or matrix view revealing whether higher shelf visibility drives better sales
- **Rating Distribution** — Customer satisfaction breakdown across outlet types and product categories
- **Interactive Filters / Slicers** — Dynamic filtering by Outlet Type, Outlet Size, Location Tier, Item Type, and Fat Content for deep drill-down analysis


## 6. ✨ Screenshot of the Dashboard

https://github.com/Goutamee/BlinkIT_grocery_dashboard/blob/main/Screenshot.png
