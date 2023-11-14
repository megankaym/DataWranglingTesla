# DataWranglingTesla

Raw data for tesla stocks and lucid stocks were already csv files
Raw data for tesla deaths was an excel file so we converted it to a .csv format

Then put all 3 csv files in R for cleaning: removed $ to make monetary values numeric, joined all 3 datasets based on date, renamed columns in the new large dataset. This R code produces a cleaned csv that has all 3 datasets and contains exploratory and insightful visualizations of the dataset.

We made this csv because we will be working in python from now on.

The TESLAVIS notebook contains code for visualizing the tesla stock and death data.

The LUCIDVIS notebook contains code for visualizing the lucid stock.



The workflow for this data wrangling project can be visualized in workflow.jpg.
