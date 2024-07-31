# Bankruptcy prediction dataset for american companies in the stock market
Bankruptcy prediction dataset related to the american companies in the stock market (1999-2018)


We provide a novel dataset for Bankruptcy prediction related to the 
public companies in the American Stock market (New York Stock Exchange and NASDAQ). 
We collected accounting data from 8262 different companies in the period between 1999 
and 2018.

According to the Security Exchange 146
Commission (SEC) a company in the American market is considered bankrupt in two cases: 
• If the firm’s management files Chapter 11 of the Bankruptcy Code to "reorganize" its business: Management continues to run the day-to-day business operations but all 
significant business decisions must be approved by a bankruptcy court. 
• If the firm’s management files Chapter 7 of the Bankruptcy Code: the company stops all operations and goes completely out of business. 

When these events occur we label the fiscal year before the chapter filling as "Bankruptcy" 
(1) for the next year. Otherwise, the company is considered alive (0).
he dataset has no missing values or synthetic and imputed added values. 
Finally, the resulting dataset of 78682 firm-year observations can be divided into three subsets according to the period of time: a training set, a validation 
set, and a test set. We used data from 1999 until 2011 for training, data from 2012 until 2014 for validation and model comparison, and the remaining years from 2015 to 2018 as a test-set to prove the ability of the models to predict bankruptcy in real never seen cases.

###### The non-anonymized version of this dataset can NOT be available because of the license used to retrieve the dataset.

<b>Citation Request</b>:
1) Pellegrino, M., Lombardo, G., Adosoglou, G., Cagnoni, S., Pardalos, P. M., & Poggi, A. (2024). A Multi-Head LSTM Architecture for Bankruptcy Prediction with Time Series Accounting Data. Future Internet, 16(3), 79.
2) Machine Learning for Bankruptcy Prediction in the American Stock Market: Dataset and Benchmarks - Future Internet MDPI 2022 <a href="https://www.mdpi.com/1999-5903/14/8/244/htm"> Web link </a>

