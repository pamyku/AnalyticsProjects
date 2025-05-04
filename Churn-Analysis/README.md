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
- Built a dashboard to for easy visualisation of churn data by various stakeholders.  

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

### 🔍 EDA Findings

- 🧓 **Age**: Older customers are more likely to churn, with churn rates increasing significantly for those over 40.
- 🌍 **Geography**: Customers based in Germany had the highest churn rates compared to France and Spain.
- 🛍️ **Products**: Customers holding more products with the bank were less likely to churn.
- 🤖 **Model**: The Random Forest Classifier outperformed other models (Logistic Regression, Decision Tree, KNN) in accuracy and F1-score, making it the best model for predicting churn in this dataset.
  

![Random Forest](https://github.com/user-attachments/assets/fe1d6465-c934-4136-a4a7-c2eba4728619)

*The ROC curve for the Random Forest Classifier shows good classification performance, with an AUC score of 0.83. This indicates the model is effective at distinguishing between churned and retained customers.*


### Customer Churn Dashboard

This dashboard is built on insights gained from a Python-based exploratory data analysis (EDA) and predictive modeling process. The EDA identified age as a key factor influencing customer churn. A deeper investigation revealed that customer churn was also influenced by geographic location (country) and account balance.




![churn analysis_dashboard](https://github.com/user-attachments/assets/db3edd2e-545a-43d9-a8d4-809548b5081b)


### 🔍 Key Insights

- The **overall churn rate** is **20%**, meaning 1 in 5 customers are leaving.
- **Germany** has the **highest churn rate**, despite having fewer churners in absolute terms than France.
- Customers aged **51–60** have the **highest churn rate**, suggesting age is a key factor in retention.
- **Younger customers (18–30)** are the least likely to churn.
- **Balance distribution** shows many customers with higher balances are still churning, especially between ages 30–50.

### 📌 Recommendations

1. **Prioritise retention efforts in Germany**  
   Although France has more churners in raw numbers, Germany has the highest churn rate. This suggests customers in Germany may be less satisfied. Focused retention strategies such as improved customer support or tailored offers could be beneficial.

2. **Address churn risk in the 51–60 age group**  
   This group shows the highest churn rate. Consider developing products, services, or engagement strategies that meet the specific needs of this demographic to improve loyalty.

3. **Engage high-balance customers more proactively**  
   Many customers with significant account balances are still churning, especially between ages 30–50. These financially valuable customers should be closely monitored and targeted with personalised retention offers.



*For more details, check out the notebook and visuals in this repository.*
