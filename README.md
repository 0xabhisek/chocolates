# chocolates
Analysis of a dataset on sales of chocolates in various countries  

🚀 Quick Statistics
Gain quick insights into your data by calculating:

Averages
Medians
Minimum and Maximum values
Range (Difference between Max and Min)
Quartiles
Formulas Explained:
Average: =AVERAGE(TABLE[COLUMN])
Replace TABLE with your data range and COLUMN with the target field (e.g., amounts or units).
Median: =MEDIAN(TABLE[COLUMN])
Range: Instead of a direct formula, reference cells:
Copy code
=MAX_CELL - MIN_CELL
Quartiles: Use the PERCENTILE.EXC formula:
css
Copy code
=PERCENTILE.EXC(TABLE[COLUMN], 0.X) 
Adjust 0.X for desired quartiles (e.g., 0.25 for Q1, 0.75 for Q3).
Pro Tip:
Drag formulas to save time when applying them to multiple fields or parameters.

🔍 Unique Items Identification
Want to filter distinct entries from your dataset? The UNIQUE formula does the job:

sql
Copy code
=UNIQUE(TABLE[COLUMN]) 
This reveals a clean list of unique products, such as:

70% Dark Bites
Choco Coated Almonds
Raspberry Choco
Organic Choco Syrup
…and more.

📊 Key Insights from the Data
Statistic	Amounts	Units
Average	4136.23	152.2
Median	3437	124.5
Minimum	0	0
Maximum	16184	525
Range	16184	525
First Quartile	1652	54
Third Quartile	6245.75	223.5
