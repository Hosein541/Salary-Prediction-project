## Project Overview
The focus of the Demographic-Based Salary Prediction project is to develop a predictive model that estimates the salaries of individuals from diverse countries and races based on their demographic attributes. These attributes encompass a range of variables, including occupation, age, gender, experience, and education. The dataset for this project, acquired from Kaggle, comprises 32,561 rows and 15 columns, with 8 independent variables and the target variable, "Salary."

### Summary and Conclusion

In this project, I aimed to predict individuals' salaries using various data preprocessing techniques and machine learning models. The steps and methodologies employed are as follows:

1. Data Cleaning and Preprocessing:
   - Handling Missing Values: Given the very few missing values, they were removed as their impact on the final prediction was negligible.
   
2. Categorical Encoding and Feature Engineering:
   - Gender Simplification: The gender feature, which initially had three categories, was reduced to two categories.
   - Education and Occupation Simplification: Unique values in the education and occupation features were reduced to simplify the model and decrease complexity.

3. Data Visualization:
   - Appropriate visualizations were created to explore and understand the data patterns and relationships.

4. Data Standardization and Labeling:
   - Data standardization was performed to normalize the features, and label encoding was applied to convert categorical variables into numerical format.

5. Model Training and Optimization:
   - The performance of two models, XGBoost (XGB) and Random Forest, was optimized using Grid Search.
   - The optimized models were then combined into an ensemble model, which resulted in a final accuracy of 95.4%.

These steps ensured a comprehensive analysis and model training process, leading to a highly accurate prediction model for individuals' salaries.
### *Developed by Hosein Mohammadi*
GitHub : https://github.com/Hosein541

LinkedIn: https://www.linkedin.com/in/hosein-mohammadi-979b8a2b2/ 

Gmail : Huseinmohammadi83@gmail.com
