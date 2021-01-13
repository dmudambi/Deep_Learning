### Homework 14 - Deep Learning 
In this homework assignment, we used two RNN's to predict daily bitcoin prices using the LSTM RNN model. We used two seperate datasets for each of the models where we use actual bitcoin prices and the other being the fear and greed index. We train them, read them and compile our findings in this markdown file. 

#### Question to Answer
Question 1 - The LSTM model for the real closing price values has a loss of 0.0086 while the fear and greed index model has a loss of 0.0727. This means that the LSTM for the real closing prices has a better model as it has lesser loss. 

Question 2 - From the final graphs of the two workfiles, we can see that the predicted values of the real closing prices model better fits the data compared to the fear and greed model. This model tracks the actual values better over time. 

Question 3 - The window size of 1 is most accurate for this data as we are trying to predict daily prices. Any window time greater than one would take into account long term trend which would not meet with our objectives. 