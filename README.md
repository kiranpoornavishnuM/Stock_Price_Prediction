In this project we use a time-series model known as Long Short-Term Memory.

The Stock Closing price data is downloaded from yahoo Finance and saved into a csv file.

Then we Plot the Closing price of the stock on a line graph.

The data type of the closing price data is integer. Now we convert the data into array using numpy

Then we Compute the Total Number of rows.

Then we split the data into training_data_set which is 80% of the total data and other 20% of the data will be testing_data_Set

Using MinMaxScaler we scale the data, Therefore now the data will range from 0 to 1.

Then we split split the train data into 2 parts</br>1) x_train[]</br>2)y_train[]

As the LSTM model expects a 3 Dimensional data we reshpe the data 

Optimizer used is 'adam.

Then we train the model with epochs 20 which indicates 20 number of passes of the entire training dataset to obtain efficiency 

Then we create the testing data set which is the other 20% of the data. Now we convert the data into array using numpy then we reshape the data from 0 to 1.

Finally we plot the grpah which consists of Acutal Price and Predicted Price







