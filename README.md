# equity_research

<img src="https://user-images.githubusercontent.com/102631336/235540916-913fa77e-3751-435d-9982-bd579476115b.png" width="575" />
<img src="https://user-images.githubusercontent.com/102631336/235540797-fd02bca9-2215-4386-9fd4-332b24dd8040.png" width="382" />


<p float="left">
  <img src="https://user-images.githubusercontent.com/102631336/235540673-d843a455-8fc7-48ec-84ed-84844c2956aa.png" width="516" />
  <img src="https://user-images.githubusercontent.com/102631336/235540700-f373be25-df1f-4605-a98c-a0be060f17c5.png" width="513" />
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/102631336/235540722-3de34719-3a9d-4f02-b129-54095b2844e4.png" width="500" />
  <img src="https://user-images.githubusercontent.com/102631336/235540743-13266b27-2717-4a3c-a3af-e542416a52f5.png" width="517" />
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/102631336/235540762-f35bcfb0-ba2e-4f7a-9004-3706ce2a640c.png" width="506" />
  <img src="https://user-images.githubusercontent.com/102631336/235540782-9b9be286-9c6b-482a-9e57-505fc0384046.png" width="484" />
</p>



### Description

The aim of this project is to utilize signal discovery and stock market price prediction techniques to create a reliable executable trading strategy. To ensure consistency, the strategy is be backtested on data not yet seen by the model. The target variable is local minima and maxima of the S&P 500 price, with features including moving averages, economic indicators, adjusted close price, etc.

### Access report
Analysis is in progress on Equity_Research.ipynb with established prediction and backtesting piepeline. Currently facing problems of overfitting and underfitting in machine learning, where models have either learned too much from the training data and are unable to generalize to new data (overfitting), or have not learned enough and are too simplistic to accurately predict (underfitting). Current focus is on improving the model to predict consistently across all classes (minima/buy, maxima/sell, neither/hold) with high accuracy and generalizability.  Later on, trade strategy will be optimized through tools like the kelly criterion.
