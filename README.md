Chocolates: Sales Data Analysis
Simple Overview
This project demonstrates the analysis of a chocolate sales dataset across various countries, using Excel to perform calculations and extract meaningful insights.

Description
This Excel project showcases a comprehensive approach to data analysis, highlighting:

Quick statistical insights such as averages, medians, and ranges.
Unique product identification using Excel formulas.
Efficient data handling and visualization techniques.
By leveraging Excel’s built-in formulas and advanced features, the project offers a practical example of analyzing real-world data effectively.

Getting Started
Dependencies
To use this project, ensure the following are available:

Operating System: Windows 10 (or newer)
Microsoft Excel: 2016 version or later
Installing
Download the File:
Clone the repository or download the Excel file directly from the GitHub Repository.
Setup:
Open the file in Microsoft Excel.
No additional installations are required.
Features
🚀 Quick Statistics
Gain insights into key metrics, including:

Average: Use =AVERAGE(TABLE[COLUMN]) to calculate the mean value.
Median: Use =MEDIAN(TABLE[COLUMN]) for the middle value.
Range: Subtract minimum from maximum using cell references, e.g., =MAX_CELL - MIN_CELL.
Quartiles: Use the formula =PERCENTILE.EXC(TABLE[COLUMN], 0.X) to determine specific percentiles.
🔍 Unique Items Identification
To identify distinct products in the dataset:

Use the UNIQUE formula:
excel
Copy code
=UNIQUE(TABLE[COLUMN])  
This filters the dataset to display only unique entries, such as:

70% Dark Bites
Choco Coated Almonds
Raspberry Choco
Organic Choco Syrup
…and more!


Exploratory Data Analysis with Conditional Formatting (CF)
This project demonstrates how to leverage Conditional Formatting in Excel to gain insights from sales data. Three approaches are explored to highlight trends, outliers, and performance indicators.

📊 Objective
Enhance data visibility through color coding and conditional rules.
Understand high sales with fewer units, identify top performers, and explore duplicate or critical values.
🛠️ Steps Performed
1. Color Scales
Applied Conditional Formatting → Color Scales to the "Amount" column.
Visualized data trends by zooming out for better insights.
2. Top/Bottom Rules
Highlighted values:
Greater than average
Top 10 items in the "Amount" column.
Sorted units to reveal high sales with fewer units.
3. Highlight Cells
Identified duplicate values for analysis.
Sorted by preference to analyze patterns.

