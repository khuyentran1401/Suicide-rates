# About this Project

Find the predictors of suicide among different countries, years, sex, generation, and age group.

# Data

The data is retrieved from [Kaggle Suicide Rates Overview 1985 to 2016](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016)

# Notebook
Access the notebook of this project [here](https://github.com/khuyentran1401/Suicide-rates/blob/master/suicide-rates-1985-2016.ipynb)

# Tools

* Numpy, Pandas
* Seaborn
* Scikit-learn

# Steps

1. Import and explore data
1. Preprocess data
    * Split traing and test set with `sklearn.model_selection.train_test_split`
    * Shuffle the data to increase randomness with `sklearn.model_selection.StratifiedShuffleSplit`
    * Merge map data to existing data
    * Drop the unimportant features
    * Transform categorical data with `sklearn.preprocessing.LabelEncoder`
    * Impute missing data with `sklearn.preprocessing.Imputer`
    * Scale data with `sklearn.preprocessing.StandardScaler`
1. Visualization
    * Countplot to find the distribution of data
    * Heatmap and pairplot to find the correlation between features
    * Geopandas to find the distribution of suicide rates accross countries in the world
     
    ![image](https://github.com/khuyentran1401/Suicide-rates/blob/master/images/Screenshot%202020-04-06%2010.20.56.png)
1. Metrics:
    * Mean squared error
    * Cross validation score
1. Model Training
    * Linear Regression
    * Decision Tree Regressor
    * Random Forest Regressor
    * Grid Search Cross Validation
    * Randomized Search CV
    
    ![image](https://github.com/khuyentran1401/Suicide-rates/blob/master/images/Screenshot%202020-04-06%2010.13.21.png?raw=true)
    
    _Compare hyperparameters for Randomized Search CV_

