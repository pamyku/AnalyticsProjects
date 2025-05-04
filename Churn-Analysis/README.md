## Bank Churn Analysis

This project analyses customer data from a European bank to identify patterns linked to customer churn (i.e., whether a customer leaves the bank). It involves exploratory data analysis, predictive modeling using machine learning, and the creation of an interactive dashboard to visualize key churn indicators and insights.

**Questions**

1. What attributes are more common among churners?
2. Can churn be predicted using the variables in the data?
3. What type of segments exist within the banks customers?

### Dataset
Source: Maven Analytics
Consists of 10,000 customers data on demographics, credit history, bank balance and whether they have churned. 

#### Project overview
- Performed exploratory data analysis (EDA) to understand customer demographics and behaviors.
- Identified key drivers of churn using statistical and machine learning techniques.
- Built a classification model to predict the likelihood of a customer churning.
- Built a dashboard to for easy visualation of churn data by various stakeholders.  

### Tools used 

- Python, scikit-learn, Power BI
- Jupyter Notebbok

### 📊 Methodology

1. **Data Cleaning**: Handle missing values, encode categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualise trends and relationships.
3. **Feature Engineering**: Create relevant features to enhance model performance.
4. **Modeling**: Train and evaluate classifiers (Logistic Regression, Random Forest).
5. **Evaluation**: Use accuracy, precision, recall, ROC-AUC to assess model.
6. **Dashboard**: Develop a dashboard to present churn insights to stakeholders.

### 🔍 Key Findings

- 🧓 **Age**: Older customers are more likely to churn, with churn rates increasing significantly for those over 40.
- 🌍 **Geography**: Customers based in Germany had the highest churn rates compared to France and Spain.
- 🛍️ **Products**: Customers holding more products with the bank were less likely to churn.
- 🤖 **Model**: The Random Forest Classifier outperformed other models (Logistic Regression, Decision Tree, KNN) in accuracy and F1-score, making it the best model for predicting churn in this dataset.

  




