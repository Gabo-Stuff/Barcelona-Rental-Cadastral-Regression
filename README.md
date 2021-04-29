# Barcelona-Rent-Cadastral-Regression
Extracting a rental and cadastral datasets, analyse and preprocess the data and make prediction with a Linear Regression model using ScikitLearn and Pandas.

The project goes through three steps:
 - Web Scraping, for extract the datasets ids to query the data from the Barcelona council website.
 - Analysing and Preprocessing, for choose the desired columns, fill the N/A values and prepare the data structure for the ML model.
 - Machine Learning, where I train the model, make predictions and evaluate the accurancing of the results.

The goal for the ML model is to get the cadastral price average, number of properties and price per square meter as features; the 73 suburbs of Barcelona city
as the labels and number of examples and predict the monthly rental price average, as the target.

["cadastral price avg.", "num. of properties avg.", "rent price €/m2 avg." x 73 suburbs] --> (prediction) --> ["rent price/month avg."]


Datasets to use:
- Average monthly rent (€/month) and per surface (€/m2 per month) of the city of Barcelona.
- Cadastral positions according to the owner's type of the city of Barcelona.
