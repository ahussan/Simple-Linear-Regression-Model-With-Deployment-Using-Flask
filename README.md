# Simple-Linear-Regression-Model-With-Deployment-Using-Flask
In this project, we used a data set where we have SAT scores and GPAs of a number of students.

The goal is to make a supervised machine learning model which can predict GPA if we provide SAT Score.

Once the model is ready, we want to incorporate this model with a Flask application so that users can interact with the model using UI.

To create the model, we used: `Python, seaborn, pandas, NumPy matplotlib`. We also used `SKlearn` for implementing the Linear Regression algorithm. `Joblib` is used to save the model just like we save a file.

Simple Linear Regression (SLR) is a statistical model that can be used to process the relationship between one dependent variable and one or more independent variables. This is one of the regression algorithms in Machine Learning. In our case, the independent variable is SAT score and the dependent variable is GPA. From the SAT score, our model is predicting GPA based on the data set we have.

Once the model is created, we used `joblib.dump()` method to save the model as `.sav` file. The next step is to create a flask app and make a connection with the saved model. We can easily load the model into our python code using `joblib.load('model.sav')`.

Lastly, we can run this app locally and interact with the model using UI or deploy the application in the cloud.
