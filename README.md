# Bike-Buyers-Analysis-Excel
An end-to-end data analysis project in Excel analyzing customer demographics and bike purchasing behavior.
# Bike Buyers Data Analysis Project (Excel)

## Project Overview
This project explores a dataset containing demographic details of 1,000 potential bike buyers. The objective was to analyze customer characteristics (such as income, age, marital status, and commute distance) and determine how these factors influence their decision to purchase a bike. 

The complete analysis, data cleaning, pivot tables, and final interactive dashboard were built entirely within **Microsoft Excel**.

## Dataset Features
The dataset contains the following attributes for each individual:
* **ID:** Unique identifier
* **Demographics:** Marital Status, Gender, Income, Children, Education, Occupation, Home Owner
* **Logistics:** Cars, Commute Distance, Region, Age
* **Target Variable:** Purchased Bike (Yes/No)
* **Engineered Feature:** `age range` (Categorized into Young, Middle-Aged, and Old)

## Key Steps Performed

### 1. Data Cleaning & Feature Engineering
* Identified and handled missing or inconsistent values.
* **Feature Engineering:** Created a custom conditional column (`age range`) to group customers into broader demographic clusters (`Young`, `Middle age`, `Old`) for better analysis.
* Standardized text formats for consistency across categories.

### 2. Pivot Table Aggregations
Generated insights by cross-referencing multiple variables against bike purchases:
* **Income Analysis:** Analyzed the average income of males vs. females relative to their purchasing decisions.
* **Age Brackets:** Counted bike sales across `Young`, `Middle age`, and `Old` groups, revealing that middle-aged individuals represent the core customer base.
* **Commute Distance:** Tracked purchase counts relative to travel distances, showing that customers with shorter commutes (0–1 miles) are significantly more likely to buy a bike.

### 3. Interactive Dashboard
Built a dynamic dashboard incorporating key charts linked to the pivot tables. 
* Includes **Slicers** (such as Region, Education, and Marital Status) to allow stakeholders to dynamically filter the charts and drill down into specific target audiences.

---

## Final Dashboard Preview
*(Note: If your uploaded screenshot file has a different name, make sure it matches the name inside the parenthesis below)*
![Excel Dashboard](image_feab82.png)

## Key Insights Discovered
1. **The Sweet Spot for Age:** The majority of bike purchases come from the **Middle age** demographic, whereas older demographics show a sharp decline in purchases.
2. **Commute Distance Matters:** Customer interest peaks significantly for those living within **0-1 miles** of their destination. Marketing campaigns should target short-distance commuters.
3. **Income Trends:** Higher average income levels correlate positively with a higher probability of purchasing a bike, particularly among male buyers.

## How to View the Project
1. Download the `Excel Project Dataset..xlsx` file from this repository.
2. Open it in Microsoft Excel to interact with the slicers, view the pivot tables, and inspect the underlying data.
