# 📌 SnapLens Cameras Sales Analysis (2023)

## 📌 Project Overview
SnapLens Cameras set ambitious sales targets for 2023, distributing budgets across regions, states, and product lines (Professional, Adventure, and Lifestyle). This project analyzes the variance between budgeted and actual sales by month, state, and region.

## 📊 Key Objectives
* Load and clean actual and budgeted sales data.
* Merge both datasets to compare planned vs. actual sales.
* Compute monthly, state-wise, and region-wise sales variance.
* Visualize the sales variances using bar charts.
* Provide data-driven recommendations for future sales planning.

## 📜 Steps Performed

### 1️⃣ Import Required Libraries
Imported necessary libraries for data manipulation and visualization.
* pandas for data handling
* matplotlib and seaborn for visualization

### 2️⃣ Load and Clean Data
Read the budgeted and actual sales data from CSV files.
Standardized column names in both datasets to ensure consistency for merging and analysis.

### 3️⃣ Aggregate Actual Sales Data
Grouped the actual sales data by month, region, state, and product to calculate the total actual quantity sold for each combination.

### 4️⃣ Merge DataFrames
Performed a left join operation to merge the aggregated actual sales data with the budgeted sales data. This aligned the actual sales figures with the corresponding budget targets based on month, region, state, and product.

### 5️⃣ Calculate Sales Variance
Computed the sales variance by subtracting the budgeted sales quantity from the actual sales quantity. This difference indicates whether sales performance was above or below the set targets.
Added a numerical month column to facilitate chronological sorting for monthly analysis and visualization.

### 6️⃣ Visualize Sales Variance
Created various bar charts to visualize the calculated sales variance across different dimensions:
* **Monthly Variance:** A bar chart to analyze sales performance trends across the twelve months of 2023.
* **Region-wise Variance:** A bar chart comparing the total sales variance for each defined sales region.
* **State-wise Variance:** A bar chart identifying the states with the most significant over or underperformance in sales.

## 📈 Insights & Findings
The analysis of sales variance revealed key insights:
* Identified specific months that exhibited the highest and lowest variance between actual and budgeted sales.
* Recognized the regions and states that demonstrated significant differences in sales performance compared to their targets.
