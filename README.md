# Banking
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.
The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age,
income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer
response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%)
accepted the personal loan that was offered to them in the earlier campaign.
We will implement Classification algorithms to differentiate people who will buy loans vs the who will not
Read the column description and ensure you understand each attribute well
Perform univariate analysis of each and every attribute - use an appropriate plot for a given attribute and
mention your insights
Perform correlation analysis among all the variables - you can use Pairplot and Correlation coefficients of
every attribute with every other attribute 
One hot encode the Education variable 
Separate the data into dependant and independent variables and create training and test sets out of them
(X_train, y_train, X_test, y_test)
Use StandardScaler( ) from sklearn, to transform the training and test data into scaled values ( fit the
StandardScaler object to the train data and transform train and test data using this object, making sure that
the test set does not influence the values of the train set) 
Write a function which takes a model, X_train, X_test, y_train and y_test as input and returns the accuracy,
recall, precision, specificity, f1_score of the model trained on the train set and evaluated on the test set 
Employ multiple Classification models (Logistic, K-NN, Naïve Bayes etc) and use the function from step 7
to train and get the metrics of the model
Create a dataframe with the columns - “Model”, “accuracy”, “recall”, “precision”, “specificity”, “f1_score”.
Populate the dataframe accordingly 
Give your reasoning on which is the best model in this case 
