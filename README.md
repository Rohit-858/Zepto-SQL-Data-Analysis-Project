#🛒 Zepto SQL Data Analyst Portfolio Project
Simulating real-world analyst workflows — from messy raw data to actionable business insights, powered entirely by SQL.


🌟 What Is This Project?
This is a complete, hands-on data analyst portfolio project built around an e-commerce inventory dataset scraped from Zepto — one of India's fastest-growing quick-commerce startups.
Whether you're cracking your first data interview or polishing your GitHub portfolio, this project mirrors how analysts actually operate behind the scenes at real retail and e-commerce companies.

🎯 Who Should Use This?
👤 Audience💡 Why It Helps📊 Aspiring Data AnalystsBuild a standout portfolio project for interviews & LinkedIn📚 SQL LearnersPractice on a real, messy, multi-column dataset💼 Interview PreppersCovers retail, e-commerce & product analytics scenarios🧪 Data EnthusiastsExplore real inventory data with business-driven queries

📌 Project Overview
The core mission of this project is to simulate how a real data analyst in the e-commerce or retail industry works. Using SQL, you will:
✅ Set up a messy, real-world e-commerce inventory database
✅ Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies
✅ Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees
✅ Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue, and more

📁 Dataset Overview

📥 Source: Kaggle — Zepto Inventory Dataset
🕷️ Origin: Originally scraped from Zepto's official product listings
🏗️ Structure: Mimics a real-world e-commerce inventory system


💡 Note: Each row represents a unique SKU (Stock Keeping Unit). Duplicate product names exist intentionally — the same product can appear multiple times across different package sizes, weights, discounts, or categories, just like real catalog data.


🧾 Schema / Column Reference
🏷️ Column📖 Descriptionsku_idUnique identifier per product entry (Synthetic Primary Key)nameProduct name as it appears on the Zepto appcategoryProduct category (e.g., Fruits, Snacks, Beverages)mrpMaximum Retail Price — originally in paise, converted to ₹discountPercentDiscount percentage applied on MRPdiscountedSellingPriceFinal selling price after discount — also converted to ₹availableQuantityUnits currently available in inventoryweightInGmsProduct weight in gramsoutOfStockBoolean flag — TRUE if item is out of stockquantityUnits per package (mixed with grams for loose produce)

🔍 Phase 1 — Data Exploration
Getting familiar with the raw data before touching anything:

🔢 Counted the total number of records in the dataset
👁️ Viewed a sample of the dataset to understand structure and content
❓ Checked for null values across all columns
🗂️ Identified all distinct product categories available
📦 Compared in-stock vs out-of-stock product counts
🔁 Detected products listed multiple times, representing different SKUs


🧹 Phase 2 — Data Cleaning
Making the data trustworthy and analysis-ready:

🗑️ Identified and removed rows where MRP or discounted selling price was zero
💱 Converted mrp and discountedSellingPrice from paise → rupees for consistency and readability


📊 Phase 3 — Business Insights
The heart of the project — answering real business questions with SQL:
🔎 Analysis-💬 Business Question
🏆 Top 10 Best-Value ProductsWhich products offer the highest discounts?
💸 High-MRP Out-of-Stock ItemsWhat premium products are we missing sales on?
💰 Revenue Potential by CategoryWhich categories drive the most estimated revenue?
🏷️ Expensive Low-Discount ProductsWhere are we leaving money on the table?
🎁 Top 5 Discount CategoriesWhich categories reward shoppers the most?
⚖️ Price Per Gram AnalysisWhich products offer the best value by weight?
📦 Weight-Based Product GroupingHow is inventory split across Low / Medium / Bulk weight tiers?
🏋️ Inventory Weight by CategoryHow much total stock (by weight) does each category hold?

📜 License
This project is for educational and portfolio purposes only. Dataset credit goes to the original creator on Kaggle.


