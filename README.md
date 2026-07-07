# 📊 Sales Intelligence System

---

# 🔎 Project Summary

This project is a fully developed **Sales Intelligence System** built using **Power BI** and **Advanced DAX**.

The solution was designed to simulate a real-world enterprise scenario where:

- 👔 C-Level Executives require high-level KPI monitoring
- 📈 Sales Teams require operational performance tracking
- 📢 Marketing requires flexible time-based performance analysis
- 🔐 Data access must be secured using role-based permissions

The focus of this project is not visualization alone — but building a scalable, secure, and decision-driven analytics system.

---

# 🎯 Business Objectives

The system enables:

- 📊 Executive KPI tracking against targets and historical benchmarks
- 📅 Multi-period time intelligence comparisons (YTD, LY, Custom Periods)
- 🔒 Role-based data access using Row-Level Security (RLS)
- 🌍 Country & continent performance visibility
- 🚚 Delivery forecasting and promotion tracking
- 📢 Marketing performance analysis with dynamic time comparison

---

# 🏢 Solution Architecture

## 📌 Data Modeling

- ⭐ Star Schema Design
- 📦 Central Fact Table (Sales)
- 📂 Dedicated Dimension Tables (Date, Product, Country, Promotion, Channel)
- 🔗 Optimized relationships and context control
- 🧹 Clean and scalable measure structure

### ⚡ DAX Techniques Used

- ⏳ Time Intelligence (YTD, LY, LY YTD, Running Total)
- 🎯 CALCULATE with context modification
- 🌎 ALLEXCEPT for continent percentage calculations
- 🥇 RANKX for dynamic Top N analysis
- 📉 Dynamic KPI variance calculations
- 🎨 Conditional formatting logic measures
- 🔐 Role-based filtering logic for RLS

---

# 📊 Executive Dashboard

Designed for strategic decision-making.

### Includes:

- 📌 KPI Scorecard (Sales, Profit, Cost, Orders, Quantity)
- 🎯 Actual vs Target %
- 📈 LY & LY YTD comparison %
- 🌍 World Map & Continent breakdown
- 📅 Monthly performance trend
- 🛒 Channel distribution
- 🏷️ Brand & Category performance

💡 Interactive tooltips provide multi-year monthly comparisons.

---

# ⚙️ Operational Dashboard

Designed for sales team performance monitoring.

### Includes:

- 📦 Order volume analysis
- 💰 Return value & discount tracking
- 🌍 Country & store-type performance
- 🔍 Drill-through pages for full historical country analysis
- 📈 Highlighted monthly trend selection

---

# 📈 Advanced Analytical Features

## ⏳ Multi-Period Time Analysis

- 📅 YTD vs LY YTD
- 🔄 Custom Period 1 vs Period 2 comparison
- ⌛ Rolling time range comparison (15 / 30 / 45 days)

### 📢 Marketing Analytics Module

- 👁️ Impressions TYD vs LY
- 📊 Custom time comparison with directional indicators
- 🔘 Button-based tab navigation using bookmarks

### 🚚 Delivery Forecasting

Orders scheduled for:

- 📅 Next 1 Week
- 📅 Next 15 Days
- 📅 Next 1 Month
- 📅 Next 6 Months

### 🎁 Promotion Activity Engine

- 📌 Dynamic count of active promotions on selected date
- ♾️ Open-ended promotions treated as active

---

# 🔐 Row-Level Security (RLS)

Implemented using a dedicated security mapping table.

### Role-based access examples:

- 👤 User A → Full access to TV & Video category
- 👤 User B → Restricted to Car Video subcategory only

This ensures data governance and controlled visibility across user roles.

---

# 🎨 UI/UX Design

- 🎨 Designed in Figma before development
- 🌙 Professional dark navy theme with teal accents
- 👔 Executive-focused layout hierarchy
- 🧭 Icon-based navigation panel
- 📐 Clean spacing and consistent formatting
- 📄 Extended page height for clarity where needed

---

# 💡 Business Impact

This solution demonstrates the ability to:

- 🏗️ Translate business requirements into scalable BI architecture
- 📊 Design executive-level KPI storytelling dashboards
- 🔐 Implement secure enterprise-grade data access
- ⚡ Build advanced DAX logic for complex time scenarios
- 🚀 Deliver structured, professional reporting solutions

---

# 🛠️ Tools & Technologies

- 📊 Power BI Desktop
- ⚡ Advanced DAX
- 🎨 Figma (UI/UX Design)
- 🌐 GitHub (Version Control & Documentation)

---

# 📁 Files Included

- 📄 **Sales Analysis.pbix** — Main report file
- 📘 **README.md** — Project documentation

---

# 🚀 How to Run

1. 📂 Open **Sales Analysis.pbix** in **Power BI Desktop**
2. 🔄 Refresh data if prompted
3. 🔐 To test RLS: **Modeling → View As → Select Role**
4. 🧭 Navigate using the left-side navigation panel
