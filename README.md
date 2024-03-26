# Google Stock Price Prediction

Notebook with my code on the Kaggle competition: [Google Stock Price](https://www.kaggle.com/datasets/shuvojitdas/google-stock-price-dataset)

# Data
train.csv and test.csv

# Code
Google_Stock_Price_Prediction.ipynb - Google Colab notebook with code that trains an LSTM model to predict future stock price trends.

# Dataset and competition description 

_Copied from Kaggle:_

Many academics and analysts have found it challenging to master the art of predicting stock values. Investors are actually quite interested in the field of stock price forecasting research. Many investors are interested in knowing the stock market's future scenario in order to make a smart and successful investment. By giving helpful information like the stock market's future direction, good and successful stock market prediction systems assist traders, investors, and analysts.

# Method

My code is based on an [LSTM model](https://pytorch.org/docs/stable/generated/torch.nn.LSTM.html).

The following hyperparameters were used during training:

'input_dim': 1, 
'hidden_dim': 64, 
'num_layers': 5, 
'output_dim': 1, 
'num_epochs': 500

# Results

Training loss curve:

![image](https://github.com/suryaR-15/google-stock-price-prediction/assets/13829518/6581cc8a-7b9b-4946-b4e6-ba8db0b72879)

Predicted vs. actual prices on the training dataset:

![image](https://github.com/suryaR-15/google-stock-price-prediction/assets/13829518/8ae7933c-5db8-42b2-a81a-b5c9efafba6c)

Predicted vs. actual prices on the test dataset:

![image](https://github.com/suryaR-15/google-stock-price-prediction/assets/13829518/eea8fcfa-89e9-4d03-b33b-df6517461fe3)

# Model

The trained model can be found [here](https://huggingface.co/suryaR-15/lstm-stock-price-predictor).
