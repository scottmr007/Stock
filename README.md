VetsinTech Project - Stock Price Forecast (up or down)

AI/ML Capstone for VetsinTech with Michael Galarnyk

Introduction: Business Problem

In this project I will try to determine the probability of Apple stock being either up or down the following day. Determination of price being up or down is of more use to us vs. an absolute price. I will first use a Random Forrest Classifier for this due to its robustness and accuracy. It fits well with classifying the stock price as up or down. Then I will use a Randomized Search CV to find the best hyperparameters, then ending with XGBoost to add a little zest.

Following data sources will be needed to extract/generate the required information:
* The stock price and earnings will come from **AlphaVantage** -https://www.alphavantage.co/.
* The Apple stock earnings quarterly data also includes analyst estimates and surprise metrics which may or may not prove useful.
