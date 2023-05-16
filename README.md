# capstone_module_24
### Project Title

Predicting House Prices using school data 

**Author**

Nishant Rishu

#### Executive summary

#### Rationale
Why should anyone care about this question?

This perspective of estimating house price using is essential to whom who are planning to purchase a house and looking to buy a house in a considering various school features 

#### Research Question
What are you trying to answer?

One of my friend was looking in to buy a house in Austin and as their kids are in school so while discussing about this problem, I came up with the idea to build a model

#### Data Sources
What data will you use to answer you question?

I am using Austin, TX House Listings from the Kaggel.com -- https://www.kaggle.com/datasets/ericpierce/austinhousingprices?select=austinHousingData.csv

#### Methodology
What methods are you using to answer the question?

I will be using the following machine learning algorithms with skicit learn for this project 
- Linear 
- Ridge Regression
- Lasso Regression

#### Results
What did your research find?

I was able to find relation between price and school feature such as 
- average school distance 
- average school rating 
- average school size

#### Link to Notebook
- https://github.com/nish8935/capstone_module_20/blob/main/Capstone.ipynb

####Conclusion:

In this project we observe that if feasible to predict the price of a housing using information such as average school distance, school rating and average school size. And we can also observe that until now Ridge regression model is the best estimator with alpha=1.023292992280754

Model Name            Training Set MSE     Dev Set MSE          best_score_      
Ridge Regression      141437798083.02994   263340420523.53955  -188961178784.74576+
Lasso Regression      142772129598.4754    262898491333.06528  -277412312590.25024+
Linear Regression     141547351842.5242    261129192220.7987   -263284257660.14557+

    
####Future Recommendation:
For extending this project we can experiment with other machine learning algorithm such as elastic search, etc. and evaluate the model performance

