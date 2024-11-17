# ADL-Assignment-1
We have used TSLA stock prices for the last year as our data, to make three different RNN models.
The models differ by the number of epochs and the learning rate. The first model has 10 epochs and a learning rate of 0.001 (standard for the ADAM optimizer). The second model has 200 epochs and a learning rate of 0.001. The last model has 200 epochs and a learning rate of 0.002.
The purpose of this assignment is to forecast future values of the stock price, and as we can see different hyperparameter values change the accuracy of the forecasts, when compared to the test data.
We can see that after 10 epochs the first model has a train loss value of 0.0027. For the second model we see that the train loss value is 0.0026 after 200 epochs. For the last model the train loss value is 0.0028 after 200 epochs.
This suggests that the most accurate model is the one using 200 epochs with a learning rate of 0.001.
