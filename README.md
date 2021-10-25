##1.Pick one use case (defined below).

Predict stock market price for TESLA. I want you to make a prediction algorithm which predicts the price of this stock on a    specific date. Input will be date and output should be price of that stock (close value in the data file). You should also show the  prediction percentage score. Data file: TESLA.csv For updated csv file, please download the data from: https://finance.yahoo.com/quote/TSLA/history?p=TSLA

##2.Explore and research which algorithm would work best for this use case (regression or classification)

Regression algorithms are mainly used to predict continuous valus such as price, salary, age, and classification algorithms is commonly used to  predict or classify discrete values such as true or false,  spam or not spam etc.
With this in mind, i think it's a nobrainer to go for a regression algorithm for this problem. 

Although, on page 14 of the 'MachineLearning-p3' powerpoint, it says that we should use a classification algorithm for stock market predictions. Due to lack of examples usinng a clasificationn algorithm on the web, we have chosen to use a recurrent neural network to train our model. 


##3.Document your findings in a file (3-5 lines) on why you chose this algorithm.

This project is build on a recurrent neural network (Further reffered to as 'RNN')
Our innspiration: https://www.youtube.com/watch?v=PuZY9q-aKLw&t=1346s

Because of the internal memory, we have chosen to use RNN due to its ability to remember importannt things about the input it recieves. 
This allows the predictions to be more precise in what's coming next. 
