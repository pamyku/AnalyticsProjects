## Gaining insights into the factors associated with health claims

### Project Overview

Healthcare insurance costs are a result of the expenses related to treatment. Personal attributes like age, gender, family size and medical conditions are sometimes used to determine a client’s insurance payments. This dataset contains information on personal attributes (age, gender, BMI, family size, smoking habits), geographical factors and medical factors (blood pressure and diabetic status). In this project, the data was used to gain insights into how these factors influence insurance claims and the use of regression analysis in estimating healthcare expenses. 

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

 Here are some images of the plots


 ### Findings
 1. There was a noticeable difference in medical expenses between smokers and non-smokers. Higher claims were apparent in smokers. 
 2. Further analyses showed a correlation between BMI and insurance claims, particularly among smokers. As the BMI increased, the medical claim also increased, particularly in smokers.
 3. Significant predictors of claim were smoking status, BMI, number of children, region and blood pressure. 
 4. The best model demonstrated the interaction between smoking and BMI, and it explained 77% of the variation in claims.
 5. Claims from the North East region were significantly higher than other regions, despite of smoking status. This suggests that while smoking status significantly impacts the claim amount, regional factors also play a crucial role in determining insurance claims. 


The significant gap between the orange and blue lines across all BMI values suggests a strong interaction effect between BMI and smoking status. Smokers with higher BMI have disproportionately higher insurance claims compared to non-smokers with similar BMI. 

### Recommendations

For Insurance Companies: This plot provides insight into risk assessment. Smokers, especially those with higher BMI, pose a greater financial risk due to higher predicted claim amounts. This might influence premium calculations and risk management strategies. 

For Healthcare Policy: The strong interaction between smoking and BMI on health-related costs highlights the importance of targeted health interventions. Programs focusing on smoking cessation and weight management could potentially reduce insurance claims.

 ### Limitations
- The non smokers in the northeast have higher claims. Future analyses are recommended to find contributory factors for the differences between the regions
- More work is needed to refine the models, like accounting for outliers.
- It will be good to look at other interractions between the variables

   
 
