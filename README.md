# Google Stock Prediction
Simple mini project with goals of predicting Alphabet Inc stock (GOOG) using TensorFlow and Keras
![1_eJWbxmatlWJCNuhJqXB_dw](https://user-images.githubusercontent.com/88265749/133384052-a1cf6a50-7263-4e5b-af4b-9731d6be2cac.png)
![1200px-Keras_logo svg](https://user-images.githubusercontent.com/88265749/133384045-0e839d03-2511-466f-a118-468941b99737.png)
# Background
Nowadays stock market are getting more popular in a young generation "Figures from the non-profit foundation AksjeNorge show that more young small investors have entered the stock market in the past year than ever before". This leads into a lot of people getting burned, Knüpfer notes that sharp stock market declines are a reality that happens at fairly regular intervals. This is when investors really lose money.
# Objective
* Construct a model that can predict stock market
* Apply TensorFlow and Keras to process a model
* Calculate loss using MAE
# Modelling Parameter
* RNN Layer : 3
* Cell : LSTM
* Unit : 256
* Dropout : 50%
* Bidirectional : False
# Training Parameter
* Loss : hubber_loss
* Optimizer : adam
* Batch size : 64
* Epoch : 500
* Ticker : GOOG
# Summary
* Predicted future price after 1 week is $2890
* Model has accuracy of 57.7%
* Profit per trade about $5
![download (8)](https://user-images.githubusercontent.com/88265749/133384088-d03e31bf-5836-422d-b550-5bd38bdfde4b.png)
