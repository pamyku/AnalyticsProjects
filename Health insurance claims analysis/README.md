## Gaining insights into the factors associated with health claims

### Project Overview

This project focuses on analysing health insurance claims data to uncover patterns, trends, and insights that can inform decision-making and improve health outcomes. In this project, the data was used to gain insights into how personal, medical and geographical factors influence insurance claims and the use of regression analysis in estimating healthcare expenses. 

### Dataset
Dataset: Healthcare Insurance  
Source: Kaggle compiled by Sumit Kumar Shukla
Variables: Age, Sex, BMI, Diabetic, Children, Smoker, Region, Claim (charges incurred by the insured person)

 ### Tools
 - Python

 ### Data Cleaning/pre-processing 
 - Loaded and inspected the data including data types
 - Checked for missing values
 - Used descriptive statitics to check data/variable distribution
 - Filled missing values by the mean (continous variables) and most frequent value (categorical variables)

### Exploratory Data Analysis

The EDA involved exploring the data to answer some key questions in the Healthcare Insurance Data
1. What is the distribution of the variables in the data?
2. Are there any existing relationships between the variables?
3. Which factors infleunce the healthcare costs or claims?

 ### Data Analysis

- Used scatter plots to assess relationshipbs between healtlth claims and age, blood pressure and BMI.
- Used box plots to visualise the relationship between claim and categorical variables like smoking status.
- Correlation matrix to check for relationships between numerical variables
- Multiple regression analysis to detemine factors that were significantly associated with the claim variable


 **Here are some images of the plots**


![claim vs smoker](https://github.com/user-attachments/assets/d402f083-37e9-4e9f-a360-7f2f1e89b54f)



![Claim vs bmi by smoker](https://github.com/user-attachments/assets/a131fa38-61b3-4943-9c39-aee57e6faec6)



### Findings
 1. There was a noticeable difference in medical expenses between smokers and non-smokers. Higher claims were apparent in smokers. 
 2. Further analyses showed a correlation between BMI and insurance claims, particularly among smokers. As the BMI increased, the medical claim also increased, particularly in smokers.
 3. Significant predictors of claim were smoking status, BMI, number of children, region and blood pressure. 
 4. The best model demonstrated the interaction between smoking and BMI, and it explained 77% of the variation in claims.
 5. Claims from the North East region were significantly higher than other regions, despite of smoking status. This suggests that while smoking status significantly impacts the claim amount, regional factors also play a crucial role in determining insurance claims.


*A plot show the interraction between smoking and BMI*


![Model with interraction](https://github.com/user-attachments/assets/e8c8c9b7-ae88-479c-ae18-6797e9b46e47)


The significant gap between the orange and blue lines across all BMI values suggests a strong interaction effect between BMI and smoking status. Smokers with higher BMI have disproportionately higher insurance claims compared to non-smokers with similar BMI. 

### Recommendations

For Insurance Companies: This plot provides insight into risk assessment. Smokers, especially those with higher BMI, pose a greater financial risk due to higher predicted claim amounts. This might influence premium calculations and risk management strategies. 

For Healthcare Policy: The strong interaction between smoking and BMI on health-related costs highlights the importance of targeted health interventions. Programs focusing on smoking cessation and weight management could potentially reduce insurance claims.

 ### Limitations
- The non smokers in the northeast have higher claims. Future analyses are recommended to find contributory factors for the differences between the regions
- More work is needed to refine the models, like accounting for outliers.
- It will be good to look at other interractions between the variables

**This is my first github project!!!** 😃 
