# Predicting stock prices using Facebook's Prophet Model 🍋 #

### 👋 Introduction ###
This is a public lemon.markets repository that showcases how to utilize Facebook's Prophet model in an attempt to forecast the close price of the Tesla Stock. The repo consists of two folders. TSLA - c prices contains the model build using the actual closing prices while TSLA - c differences contains 3 models build using the price difference, price log difference and price percentage difference.

You can find an article linked to this repo here

### Quick Start 🏃‍♂️: ###
1. sign up to lemon.markets
2. clone this repo
3. Change the market_data_api_key in get_data.py with your personal lemon.markets API key
4. run get_data.ipynb to get the csv file containing the stock data
5. run prophet-model-v3-Hyperparameter tuning.ipynb two evaluate the best values for your parameters
6. feed the parameters from step 5 into your model in tuned_model.ipynb
7. forecast away

### 🔌 API Usage ###
This project uses the lemon.markets API and the lemon.markets Python SDK.

🍋 lemon.markets is a brokerage API by developers for developers that allows you to build your own experience at the stock market. We will use the Market Data API and Trading API to build a mean reversion trading strategy in this project!

If you do not have a lemon.markets account yet, you can sign up at lemon.markets.


##### Contribute to this repository #####
lemon.markets is an API from developers for developers and this (and all lemon.markets open source projects) is(are) a work in progress. Therefore, we highly encourage you to get involved by opening a PR or contacting us directly via support@lemon.markets.

Looking forward to building lemon.markets with you 🍋
