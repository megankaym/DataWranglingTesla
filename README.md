# DataWranglingTesla

Raw data for tesla stocks and lucid stocks were already csv files
Raw data for tesla deaths was an excel file so we converted it to a .csv format

Then put all 3 csv files in R for cleaning: removed $ to make monetary values numeric, joined all 3 datasets based on date, renamed columns in the new large dataset. This R code produces a cleaned csv that has all 3 datasets and contains exploratory and insightful visualizations of the dataset.

We made this csv because we will be working in python from now on.

The TESLAVIS notebook contains code for visualizing the tesla stock and death data.

The LUCIDVIS notebook contains code for visualizing the lucid stock.



The workflow for this data wrangling project can be visualized in workflow.jpg.

Resources
https://www.tesladeaths.com/
Bachman, Elon, and I Capulet. “Digital Record of Tesla Crashes Resulting in Death.” Tesla Deaths, Tesla Deaths, 29 Sept. 2023, www.tesladeaths.com/.
Tesla, Inc. (TSLA) Historical Data | Nasdaq
“TSLA Historical Data .” Nasdaq, www.nasdaq.com/market-activity/stocks/tsla/historical. Accessed 8 Nov. 2023.
https://www.nasdaq.com/market-activity/stocks/lcid/historical
“LCID Historical Data.” Nasdaq, www.nasdaq.com/market-activity/stocks/lcid/historical. Accessed 8 Nov. 2023.
https://www.investopedia.com/articles/active-trading/072115/what-makes-teslas-business-model-different.asp  

https://blog.gitnux.com/companies/lucid-motors/  

https://www.kaggle.com/code/majinx/tesla-stock-price-prediction-using-lstm/notebook
Majinx. “Tesla Stock Price Prediction Using LSTM.” Kaggle, Kaggle, 8 Feb. 2023, www.kaggle.com/code/majinx/tesla-stock-price-prediction-using-lstm/notebook. 
