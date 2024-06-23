## Stock Price Prediction and Forecasting
This notebook is our submission to the Kaggle Hackathon hosted by PES University, which secured an impressive <b>5th position out of 274 teams on the leaderboard</b>.

It contains various methods and models used to predict the closing price and the corresponding strategy employed by each model, along with a comparison between the various models used.

### Description
This project involves stock price analysis and forecasting using various machine learning models and techniques. Our objective was to predict the closing price of stocks and devise optimal trading strategies.

### Technologies Used
* Python
  * SciKit Learn
  * Matplotlib
  * NumPy
  * Pandas
### Key Highlights
* <b>Data Engineering</b>:
  
  Applied data engineering techniques to derive new features from fundamental columns like Open, Close, and Volume.
* <b>Forecasting Models</b>:
  
  Utilized SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors) and MLR (Multiple Linear Regression) to accurately forecast closing prices by capturing seasonality and trend patterns.
* <b>Classification Models</b>:
  
  Employed various classification models to forecast optimal trade strategies, achieving the highest accuracy of 81% with SVM (Support Vector Machine).
  Other models used include KNN (K-Nearest Neighbors), XGBClassifier (Extreme Gradient Boosting), and RandomForestClassifier.
