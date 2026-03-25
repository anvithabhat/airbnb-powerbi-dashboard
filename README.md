# 🏠 Airbnb Performance Dashboard (Power BI)

## 📊 Project Overview

This project presents an interactive Power BI dashboard analyzing Airbnb performance across multiple dimensions such as listings growth, customer review behavior, market concentration, pricing trends, and host trust factors.

The dashboard provides actionable insights into user engagement patterns, seasonal trends, and host credibility using advanced DAX and visualization techniques.

---

## 🎯 Objectives

* Analyze Airbnb listing growth over time
* Understand customer review frequency and engagement
* Identify top-performing cities and market concentration
* Explore seasonal trends in reviews
* Evaluate host trust factors (verification & profile completeness)

---

## 📂 Project Files

Due to file size limitations, the Power BI file and dataset are hosted externally:

🔗 **Power BI File (.pbix):**
https://drive.google.com/file/d/10N8qy4Jiqe7o-pGyWBSMWlzpBl2BP53i/view?usp=sharing

🔗 **Dataset (CSV - Listings):**
https://drive.google.com/file/d/1AsOG2a3-SYhrxYlCjDXGhEmu6mWnxXA0/view?usp=sharing

🔗 **Dataset (CSV - Reviews):**
https://drive.google.com/file/d/1boEUBLyejoIytJwIGSctQWgxYeh1pgnP/view?usp=sharing

---

## 📌 Key Features

### 🔹 Overview Dashboard

* Total Listings, Hosts, Cities, Property Types, Reviews
* Lifecycle analysis (Introduction → Growth → Maturity → Decline → Reinvention → Covid)
* Room type distribution trends

### 🔹 Ratings Analysis

* City-wise rating comparison
* Bookmark-based toggle:

  * ⭐ Overall Ratings
  * 🔍 Detailed Ratings (Accuracy, Cleanliness, etc.)
* Pareto analysis (Top cities contribution)
* Average price comparison by room type

### 🔹 Review Analysis

* Review frequency distribution (Pareto curve)
* Insight: ~99% of users leave ≤3 reviews
* Seasonality analysis using ribbon chart
* Trust Factor visualization (Host verification & profile completeness)

---

## 📷 Dashboard Preview

### Overview
![Overview](overview.png)

### Ratings - Overall View
![Ratings Overall](ratings_overall.png)

### Ratings - Detailed View (Bookmark)
![Ratings Detailed](ratings_detailed.png)

### Reviews
![Reviews](reviews.png)

---

## 🧠 Key Insights

* 📈 Airbnb shows rapid growth until 2015 followed by maturity and stabilization
* 🌍 Paris, New York, and Sydney contribute nearly 50% of total listings
* ⭐ Cape Town leads in overall service quality
* 👤 Most users are one-time reviewers; repeat engagement is minimal
* 📅 Paris & Rome dominate summer months, while New York peaks during holidays
* 🛡️ Over two-thirds of hosts are fully verified, ensuring platform trust

---

## 🛠️ Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

---

## 🔧 Key DAX Concepts Used

* CALCULATE & FILTER
* ALL / ALLEXCEPT (context control)
* RANKX (ranking)
* Cumulative calculations
* DISTINCTCOUNT vs COUNT
* Bookmark-based interactivity

---

## 🚀 How to Use

1. Download the `.pbix` file from the link above
2. Open in Power BI Desktop
3. Interact with filters, bookmarks, and visuals

---

## 👩‍💻 Author

**Anvitha Bhat**
