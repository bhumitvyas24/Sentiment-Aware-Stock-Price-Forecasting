Sentiment-Aware Stock Price Forecasting

Description
This project develops a deep learning model to forecast daily stock prices for major tech companies by integrating financial market data with NLP-driven sentiment analysis from over 80,000 real-time tweets. The model uses a dual-branch LSTM/GRU network to capture both long-term and short-term trends, resulting in highly accurate predictions.

Features
* Data Integration: Combines time-series financial data with unstructured text data from Twitter.

* Sentiment Analysis: Leverages a pre-trained FinBERT transformer model for nuanced financial sentiment scoring.

* Time-Series Forecasting: Implements a dual-branch LSTM/GRU network to predict next-day closing prices based on 20-day historical sequences.

* Granular Evaluation: Includes performance analysis for both the overall model and individual stocks with specific metrics.

Tech Stack

Python

* Pandas & NumPy for data manipulation

* TensorFlow & Keras for building the deep learning model

* Scikit-learn for data scaling and evaluation

* NLTK & Hugging Face Transformers for NLP tasks

* Matplotlib & Seaborn for data visualization

Results
The model achieved high predictive accuracy on unseen test data, resulting in an overall R-squared of 0.94, a Mean Absolute Percentage Error (MAPE) of 7.49%, and a Mean Absolute Error (MAE) of $13.77.



Apple (AAPL) - Actual vs. Predicted Prices
(Replace with the link to your saved AAPL_prediction_plot.png)
