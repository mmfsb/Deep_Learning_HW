# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. I will build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

I used deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

## Build the Model
![buildthemodel.png](Images/buildthemodel.png)
---
## Summarize the Model
![summarizemodel.png](Images/summarizemodel.png)
---
## Fear and Greed Index Model Train
![fngmodeltrain.gif](Images/fngmodeltrain.gif)
---
## Fear and Greed Real vs Predicted Prices
![fngrealvspredicted.png](Images/fngrealvspredicted.png)
---
## Fear and Greed Index Plot
![fnghvplot.gif](Images/fnghvplot.gif)
---
## Bitcoin Closing Prices Model Train
![bitcoinclosingpricetrain.gif](Images/bitcoinclosingpricetrain.gif)
---
## Bitcoin Closing Prices Real vs Predicted Prices
![btccrealvspredicted.png](Images/btccrealvspredicted.png)
---
## Bitcoin Closing Prices Model Plot
![bitcoinclosingpricehvplot.gif](Images/bitcoinclosingpricehvplot.gif)
---

<details>
<summary> Which model has a lower loss? </summary><br>
 - Bitcoin closing prices<br>
</details>
<br>

<details>
<summary> Which model tracks the actual values better over time? </summary><br>
 - Bitcoin closing prices <br>
</details>
<br>

<details>
<summary> Which window size works best for the model? </summary><br>
 - A window size of 2 <br>
</details>
<br>
- - -
