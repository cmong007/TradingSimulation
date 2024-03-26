**<h1> Trading Simulation Project</h1>**

<h3>Description</ins></h3>
This projects aims to validate a trading strategy based on "Fearful" and "Greedy" market sentiments based on historical VIX.

<h3>Tools</h3>

- Python (Time Series)

<h3>Data set</h3>

- [ADJ_CLOSE.csv]()

<h4>Data exploration</h4>

- Consists of data from 1990 to 2020
- 7881 Records with missing values involving stock price only
- VIX column
- 2588 columns of stock tickers

<h3>Implementation</h3>
 
-  The daily sentiment index (DSI) was constructed using the rolling 12-months historical median VIX data.
-  Based on the DSIs, the monthly sentiment index (MSI) was constructed by taking the overall DSIs for the month.
-  The trading signals was generated on the sentiments indicated from the MSI.
-  Simulation was conducted on data from 1991-2010
-  Validation of strategy was conducted on data from 2010-2020

</br>

<h3>Results/Findings</h3>
Based on simulation phase the top 5 performing stocks were tickers #145 , #1555 , #2052 , #2206 and #1862.
</br></br>

Simulation profits:
</br>
<img src = ''/>
</br>
Validation profits:
</br>
<img src =''/>




