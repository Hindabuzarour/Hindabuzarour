# Prediction of Product Sales
### Overview of the project
Prediction of Product Sales it is a critical process for business planning and decision-making, involving the use of data analysis and statistical models to predict future sales, the outcomes from this project is to predict the sales items in different outlet type.
During the exploratory data analysis, a countplot was visualized for each numeric datatype column. 
Also, a barplot was visualized for each categorical column. 
This gave a good baseline for all of the numeric and categorical columns.
### Business problem
The goal is to help businesses understand which factors impact sales and to forecast the item outlet sales, accurately predicting sales performance is critical for making data-driven decisions, this help the retailer understand the properties of products and outlets that play crucial roles in increasing sales, improving efficiency, and increasing revenue.
### Data
The data used for this project is sourced from the company, the main objective of this dataset is to understand how various factors impact Sales of the product in the particular store and to predict future outlet sales. The data include features about outlet type & location, item type, item weight & Maximum Retail Price!
. We use Item_Outlet_Sales as a target 

- Number of Observations: 8523
- Number of Features: 12
### Methodology
- Data Cleaning: Checking for missing values, duplicates, and outliers
- Exploratory Data Analysis (EDA): Check distributions and relationships between features 
- Data Preprocessing
- Model Selection: Selected several machine learning models to compare performance
- Model Evaluation
  
### Result

#### Heatmap to examine correlations between numerical variables 
![download (2)](https://github.com/user-attachments/assets/2d334a51-0d37-4aaa-974e-f487740e65dc)
- Positive moderate relationship between iteam outlet sales and	maximum retail price (list price) of the product
  
#### Item type 
![download](https://github.com/user-attachments/assets/6d5cb623-5f3e-4701-b242-0e546c674b89)
- The polt shows  that the majority of the item sales are fruit and vegetables

####  Sales item in different outlet type
![download (1)](https://github.com/user-attachments/assets/61bd22ef-834c-4123-8fd0-a3c48a327c42)
- The highest sales are in Supermarket Type 3 compared with the other types

### Model
The final model used is a Random Forest Regressor.
The model is able to explain 60% of the features that lead to changes in Item Outlet Sales, the model predictions for the new data are close to true outlet sale by 736 USD

### Conclusion
We trained multiple machine learning models and evaluated their performance, the Random Forest Regressor is the best model it can predict the item outlet sales with minimum error. 

### Recommendations
- As we say the model is able to explain 60% of the features that lead to changes in Item Outlet Sales for new dataset, this suggests that while the model provides useful insights, but there is still room for improvement the model, by incorporating additional features that might have been overlooked or increase the observation. This lead to minimize the error.

### For further information
For any additional questions, please contact Hindabuzarour@gmail.com
  
