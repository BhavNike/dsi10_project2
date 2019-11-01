# dsi_10_sg_project2.rev

# Background:

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses in the town of Ames, Iowa state USA.

# Problem Statement:

To develop a Linear Regression model for the Prediction of Saleprice of property using data available from Ames Iowa
Data Dictionary: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
Details of the competition/dataset: DSI-US-6 Regression Challenge

# Procedure:

    Download data in dataframe format
    EDA of data
    Checking for null values and replacement with valid values if needed
    Coverting all catergorical (ordinal and nominal) data to integers and floats
    Identifying features that have considerable correlation to the target variable (namely 'SalePrice')
    Preparing and testing models to identify best fit for prediction of target variable
    Compiling of predictions of models and uploading same to Kaggle to identify suitable model
    Comments and observations during the process

# Details:

3 models were tried during the design process, with features derived from Filtering using dorrelation and Recursive Feature Elimination methods. Variations, such as, lasso, ridge, polynomial model and inclusion of engineered feature were explored, along with the baseline model of linear regression.

# Outcome:

Although the scores of some of the models were in the same range, the final model was decided based on the lowest Kaggle score. This was the Ridge Regression model with 17 features. While it is not possible to design the perfect model, it may be possible to better fit the model by further exploring on the features as well as increasing the degree of the polynomial model, selecting other features or trying other models

