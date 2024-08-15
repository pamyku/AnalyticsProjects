## Plant growth prediction  

### Project Overview

In this Plant Growth Data Classification, dataset, the prediction task involved predicting or classifying the growth milestone of plants based on the provided environmental and management factors. Predictions were based on soil type, sunlight hours, water frequency, fertiliser type, temperature, and humidity. This prediction task helps to understand how different conditions influence plant growth and such data would be valuable in optimising agricultural practices or greenhouse management.

### Dataset
Dataset: Plant Growth Data Classification (n=193) 
Source: Kaggle 

**Variables:** 
- Soil_Type: The type or composition of soil in which the plants are grown.
- Sunlight_Hours: The duration or intensity of sunlight exposure received by the plants.
- Water_Frequency: How often the plants are watered, indicating the watering schedule.
- Fertilizer_Type: The type of fertilizer used for nourishing the plants.
- Temperature: The ambient temperature conditions under which the plants are grown.
- Humidity: The level of moisture or humidity in the environment surrounding the plants.
- Growth_Milestone: Descriptions or markers indicating stages or significant events in the growth process of the plants.

### Tools
 - Python
 - Scikit learn

### Data Cleaning
 - Loaded and inspected the data including data types
 - Checked for missing values (No missing data)
 - Used descriptive statistics to check the distribution of the variables
 - Computed frequences for categorical data

### Exploratory Data Analysis

EDA involved exploring the data to check for any correlations between the variables
1. Correlation matrix to assess correlation between numerical variables
2. Explore any existing relationships between growth milestone and categorical variables
The EDA showed that fertiliser type had some influence on growth. No fertiliser resulted in less growth.

### Feature Engineering

- Created the features and labels for classsification
- Created dummies for categorical variables
- Split the dataset into train and test sets. 30% of the data was reserved as the test set

### Models

#### Decision Tree Classifier

With limited data, decision trees can overfit, meaning they might capture noise rather than the actual pattern. To mitigate this, I set constraints on tree depth. 
- Used gridsearchcv to find the best parameters for the classifier. 

*Accuracy = 58.6%*

**Feature importance**


![features](https://github.com/user-attachments/assets/1b265617-f2d3-4987-8354-9b44f5e5f309)



#### K-Nearest Neighbours

Conducted hyper-parameter tuning to find the best n. 


![knn-n](https://github.com/user-attachments/assets/c3755dbc-9776-4b69-b38c-76a36818a63e)


The final model had an accuracy of:
- *Accuracy = 62.1%*

### Model improvements
- Requires a larger sample size
- More variables like carbon dioxide concentration, air pollution, vegetation etc
- **Classification trees** Could use ensemble and boosting algorithims for classification
- **KNN** Experiment with other distance metrics and other parameters.

**Cheers!!** 😃
