# Barcelona-Rent-Cadastral-Regression
Extracting a rent and cadastral datasets, analyse and preprocess the data and make prediction with a Linear Regression model using ScikitLearn and Pandas.

The project goes through three steps:
 - Web Scraping, for extract the datasets ids to query the data from the Barcelona council website.
 - Analysing and Preprocessing, for choose the desired columns, fill the N/A values and prepare the data structure for the ML model.
 - Machine Learning, where I train the model, make predictions and evaluate the accurancing of the results.

The goal for the ML model is to get the cadastral price average, number of properties and price per square meter as features; the 73 suburbs of Barcelona city
as the labels and number of examples and predict the monthly rent price average, as the target.

The data structure to feed the model will be:

(suburbs)                cadastral price avg. | num. of properties avg. | rent price €/m2 avg. | prediction |  rent price/month avg.
1.  el Raval                    ...                      ...                      ...          |  ------->  |
2.  el Barri Gótic
...
73. la Verneda i la Pau


Datasets to use:
- Average monthly rent (€/month) and per surface (€/m2 per month) of the city of Barcelona.
- Cadastral positions according to the owner's type of the city of Barcelona.
