# DATA1030-project: Stock Sentiment Analysis and Price Forecasting
Repository for individual project in DATA1030 2023 at Brown.

Author: Jessica Yang
![sentiment analysis on Stock](image.png)

## Abstract(Introduction)

In real stock market, prices can be affected by many factors, such as the investment size, policy, and transactions. However, nowadays, most stock investors make decisions on whether to buy or sell their stocks based on the trending news. When people realize that the price of a particular stock will rise, they will buy the stock. On the other hand, if they realize that the price of the stock will decline, they can sell it. With the real-time information available to us on massive social media platforms like Twitter, facebook, we have the ability to get an important insight on stock’s performance based on general public opinions. 

In this project, I want to investigate the impact of investors’ reviews on the stock prices by Natural language approach’s sentiment analysis, which is used to rate the language used in a body of text. This project contains several stages: Data web-crapping review text data from Twitter, Exploratory Data Analysis, Sentiment analysis for specific stock, and evaluation. Furthermore, I will build a price prediction deep learning model(LSTM) by training of sentiment scores in a time-series dataframe, and try to predict future the stock prices on some typical company in S&P 500.  


## Directories
***
* Data: The Data directory contains datasets I used for this project.

* Img: the images created throughout this repository.

* Notebooks: Main notebook 

## Files

* README.md Contains the text on this page.

* requirements.txt Python libraries used in the notebooks.

# requirements
python3.10
pandas==1.3.0
pip install keras==2.6.0
