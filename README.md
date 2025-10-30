# 🚀 Blinkit Sales & Store Performance Dashboard

[![Power BI](https://img.shields.io/badge/Made%20with-Power%20BI-blue.svg?style=for-the-badge&logo=powerbi)](https://powerbi.microsoft.com/)

> An interactive Power BI dashboard analyzing Blinkit's item sales, product categories, and store performance from a provided CSV dataset.

This project transforms the raw `BlinkIT Grocery Data.csv` into a dynamic, user-friendly, and actionable tool for strategic business insights.

---

## 📊 Our Dashboard Preview

Here is a look at the main dashboard's "control center."

[![Blinkit Dashboard Preview](blinkit%20dashboard%20image.jpg)](Blinkit%20PowerBi%20Project.pbix)

*(See the full interactive version by downloading the `.pbix` file)*

---

## ✨ Project Objective

The goal wasn't just to make charts; it was to answer key business questions by turning a complex raw data file into a *clear signal*.

The dashboard was built to answer:
* What are our **best and worst-performing** product categories?
* Which **type of store** generates the most revenue?
* How do store **size, location, and type** interact to influence sales?

---

## 💡 Key Features

* **At-a-Glance KPIs:** The main page features clear, top-line metrics for `Total Sales`, `Total Items Sold`, `Average Rating`, and `Average Sale Price`.
* **Dynamic Slicers:** The user is in full control. "Slice and dice" the entire report by `Outlet Location Type`, `Outlet Type`, `Item Fat Content`, and `Item Type`.
* **User-First "About" Panel:** A built-in `(i)` info button opens a special panel explaining the report's purpose, data sources, and metric definitions. This ensures the dashboard is accessible and trusted by all users, not just data experts.
* **Deep-Dive Visuals:** Rich charts analyze sales from every angle, including by category, store type, store size, and more.

---

## 📈 Data Deep Dive & Project Scope

This dashboard is powered by a single data file: `BlinkIT Grocery Data.csv`.

### A Critical Note on Data Scope

A core part of this project was understanding the data's limitations and building the analysis correctly.

> **What We Have:** Item-level transaction data. This is perfect for analyzing **Product Sales** and **Store Performance**.
>
> **What We Don't Have:** Order-level or customer data (e.g., `Order ID`, `Customer ID`).

Because of this, the dashboard is laser-focused on accurate, provable insights. It **is not** designed to analyze customer-specific metrics like "Average Order Value (AOV)" or "Customer Churn," which would be impossible to calculate.

---

## 🏆 Key Insights & Discoveries

This analysis uncovered several clear, actionable insights:

1.  **The Product Story:** The data clearly shows that **[e.g., Snack Foods and Fruits & Vegetables]** are the undisputed revenue champions, accounting for over X% of all sales.
2.  **The 'Winning Store' Formula:** A "golden formula" for the highest-performing outlets emerged from the data:
    * **Type:** `Supermarket Type1` is the most successful model.
    * **Location:** `Tier 3` locations generate the highest sales.
    * **Size:** `Medium` sized stores hit the revenue sweet spot.
3.  **Consumer Preference:** We found a surprising trend: **"Low Fat"** items consistently outsell "Regular" fat items across most categories.

---

## 🛠️ Tools Used

* **Microsoft Power BI Desktop:** Used for all data modeling, DAX calculations, and visualization.

---

## 📖 How to Use

1.  **View the Dashboard:**
    * Download the `Blinkit PowerBi Project.pbix` file.
    * Open it using Microsoft Power BI Desktop.
2.  **Explore the Data:**
    * The raw `BlinkIT Grocery Data.csv` file is included in this repository for your own analysis.
