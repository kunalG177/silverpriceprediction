# silverpriceprediction
Introduction:
The aim of this machine learning project is to predict the future price of silver using logistic regression. 
Silver is a precious metal that is widely traded and has a significant impact on the global economy. Therefore, 
predicting its price can be beneficial for investors and traders.

Data:
This data file is a Comma separated value file format with 2290 rows and 7 columns. It contains 5 columns which 
are numerical in datatype and one column in Date format. Clearly the data shows value of the variables SPX,GLD,USO,SLV,EUR/USD 
against the dates in the date column.

Data preprocessing:
The dataset is then split into training and testing sets in a 80:20 ratio. The training set is used to train the 
logistic regression model, while the testing set is used to evaluate its performance.

Model training:
Logistic regression is applied to the training set using the logistic regression function from the Scikit-learn library. 
The default hyperparameters are used for this model. The model is then fitted to the training set to learn the relationship 
between the features and the labels.

Model evaluation:
The performance of the logistic regression model is evaluated using the testing set. The accuracy score is used to evaluate 
the performance of the model. The accuracy score is defined as the number of correctly classified instances divided by the 
total number of instances. 

Conclusion:
The logistic regression algorithm was applied to the Silver Futures dataset to predict the future price of silver. The model 
achieved an accuracy score which is not a good result. The misclassification of instances indicates that the model needs to 
be improved. Future work could include trying different machine learning algorithms, feature engineering, or hyperparameter 
tuning to achieve a better result. It is also essential to keep in mind that predicting the future price of silver is a complex
task that involves several external factors such as global economic conditions, political events, and natural disasters.
