# chocolates
Analysis of a dataset on sales of chocolates in various countries  

🚀 Quick Statistics
Gain quick insights into your data by calculating:

Formulas Explained:
Average: =AVERAGE(TABLE[COLUMN])

Replace TABLE with your data range and COLUMN with the target field (e.g., amounts or units).

Median: =MEDIAN(TABLE[COLUMN])

Range: Instead of a direct formula, reference cells:

=MAX_CELL - MIN_CELL
Quartiles: Use the PERCENTILE.EXC formula:


=PERCENTILE.EXC(TABLE[COLUMN], 0.X) 
Adjust 0.X for desired quartiles (e.g., 0.25 for Q1, 0.75 for Q3).


🔍 Unique Items Identification
Want to filter distinct entries from your dataset? The UNIQUE formula does the job:

=UNIQUE(TABLE[COLUMN]) 
This reveals a clean list of unique products, such as:

70% Dark Bites
Choco Coated Almonds
Raspberry Choco
Organic Choco Syrup
…and more.


