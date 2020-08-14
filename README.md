# Employee Salary Prediction 
![](static/images/21.png)

Simple application has to predict employee salary depending up on different factors
* Created an app that Predicts Salary based on Their Experience .
* Data collected from Open source websites from Internet .
* To collect data i had used Selenium for Scraping.
* Processed features to make data look's like perfect and to get good score with less loss.
* I had used Linear Regression,Logistic Regression ,And some other to reach best model
* Finally Deployed model on Heroku to make use any where in the world .

## Code and Resources Used :
* Python Version : 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle
* For Web Framework Requirements: pip install -r requirements.txt


## Data Cleaning :
> I had applyed Data Cleansing Techniques on data set.

## Model Building :
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
I tried three different models and evaluated them using  MAE. I chose MAE Because it's better to understand performance of our model .
I tried Five different models:

* Logistic Regression
* Linear Regression
* RandomForest Regressor
* Decision Tree Regressor

## Model Performance :
* Model performance can be evaluated on different metrics some of metrics are 
  * Mean Square Error
  * Mean Absolute Error
  * Root Mean Square Error 
## Productionization :
* In this step , I had deployed Model on heroku with Flask api.
* The API endpoint takes in a request with a values by end user and returns Predicted Salary . Here check it out  [Employee Salary Prediction Web App](https://salarypredictionex.herokuapp.com/)


## References :
https://towardsdatascience.com/web-scraping-using-selenium-python-8a60f4cf40ab  <br>

https://www.pluralsight.com/guides/web-scraping-with-selenium <br>
 
https://www.kaggle.com/c/job-salary-prediction  <br>

https://data.world/datasets/salary <br>
