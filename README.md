
![uber](https://github.com/Kamuthuj/Uber-stock-prediction/assets/121629618/dcb5d5fd-75d2-4100-93cc-08cc1c632826)

In the project I aimed to predict uber stock prices. Using public data on their website, I performed data cleaning and extracted new columns such as individual years and months.I was able to see how trading volumes changed over the months. I created a correlation matrix to establish the strength of the relationships within the variables. I splitted data into training and testing where i used around 80% for training. 

![Dtree model](https://github.com/Kamuthuj/Uber-stock-prediction/assets/121629618/d8d48a2c-e532-49f8-83db-88530937879d)

I used the linear regression and decision tree model to train the data. Both models performed equally the same having a mean squared error of about  3.067. This prompted me to do hyperparameter tuning to get the best model and  hyperparameters and perfomed Grid search. This reduced the mean squared error to 0.28 proving that the model worked well.
