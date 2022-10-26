# Prediction-of-Galaxies-Well-Being
### Galaxies Data Analysis & Prediction Modeling

### Data Description
The data contains 80 variables that characterize the demographic and socio-economic situation of 181 galaxies over a period of at most 26 years. A composite index is given that measures their well-being. However, the demographic and socio-economic variables that influence this index is not known. We seek to determine, what makes the galaxies better off?

#### Defining the question
1. Tell us which variables best explain the variance of the well-being index
2. Determine the future well-being values of the galaxies

### Metric for Success
1. Come up with a model that will be used to predict the future well-being index values of galaxies.
2. Test the model using the RMSE Metric. The lower the RMSE score, the more accurate the model.
3. Predict the future well being index values using the provided validation dataset.

### Experimental Design
Import necessary libraries

Import dataset

Exploring data

Data cleaning

1. Checking & handling missing values
2. Checking for duplicates
3. Checking for outliers

EDA

1. Checking the distribution of the features
2. Multivariate analysis
3. Variance Threshold

Modelling

1. Linear Regression
2. Lasso Regression
3. Ridge Regression

Validating the model

By fitting the most accurate model into our cleaned validation data.

### Data Relevance

Check for data relevance by checking the columns with null values and selecting the columns which contained missing values that were less than 30 %, which were only 12 columns. The rest of the columns had too many missing values which would not really be relevant when trying to fit our models because they contained very little information.
