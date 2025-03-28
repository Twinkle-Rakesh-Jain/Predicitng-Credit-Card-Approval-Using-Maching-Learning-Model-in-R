# Predicitng-Credit-Card-Approval-Using-Maching-Learning-Models-in-R

# Project Description:
This project aims to develop a machine learning model that predicts the approval or rejection of credit card applications based on socio-economic parameters such as income group, profession, and assets owned. Utilizing a dataset containing over 1 million records, the study assigns a credit score to applicants and classifies them as good or bad clients based on their risk profiles. By applying supervised machine learning techniques, the project seeks to improve the accuracy and efficiency of credit risk assessment, thereby assisting financial institutions in making data-driven lending decisions.

# Project Execution:

## Data Collection & Preprocessing:

a. The dataset was obtained from Kaggle and contains 1,048,575 records with 19 variables categorized into numerical and categorical attributes.

b. Data cleaning was performed to handle missing values, outliers, and inconsistencies, replacing missing values with median values.

c. One-hot encoding was used for categorical variables to facilitate machine learning model training.

## Exploratory Data Analysis (EDA):

a. Various visualizations were created to examine the influence of socio-economic factors on credit card approval.

b. Insights were derived from demographic trends, including the impact of education level, family status, and income category on creditworthiness.

c. Key observations included a higher default rate among individuals with lower education levels and an increased probability of default for larger family sizes.

## Key Insights:
a. The graph shows the percentage of defaulting and non-defaulting customers with respect to their number of children.
![viz 1](https://github.com/user-attachments/assets/073e9bc4-30b1-458f-ae15-eaab26900883)

b. The graph shows the percentage of defaulting and non-defaulting customers with respect to their level of education.
![viz 2](https://github.com/user-attachments/assets/aaa176ce-ff4c-4e3a-a70a-eca15a4a755e)

c. The graph shows the rate of default and timely payments with respect to family status.
![viz 3](https://github.com/user-attachments/assets/27963dab-b0c2-46f3-998d-dc1f9106532c)

d. The graph displays the distribution of credit card ownership and payment behaviour based on different income statuses.
![viz 4](https://github.com/user-attachments/assets/ac2a7b48-8e6c-4458-8035-48962a488fe2)

e. The two graphs provided showcase an interesting insight into the distribution of credit card holders who defaulted and those who did not. The graph on the right illustrates a bell curve distribution, which is typically associated with normal distribution, whereas the graph on the left highlights the data distribution of credit card holders who defaulted.
![viz 5](https://github.com/user-attachments/assets/3d7b2772-50d4-4200-9690-a6fda15c762f)


## Model Development & Validation:

a. Multiple supervised machine learning algorithms were implemented, including logistic regression, decision trees, and random forest classifiers.

b. Performance metrics such as accuracy, precision, recall, and F1-score were utilized to evaluate model effectiveness.

c. Random forest emerged as the most effective algorithm, leveraging its ability to handle non-linear relationships and imbalanced data.

## Model Optimization:

a. Hyperparameter tuning was conducted to improve prediction accuracy.

b. Feature selection techniques were applied to identify the most significant variables influencing credit approval.

c. The final model was validated using cross-validation techniques to ensure robustness.

# Conclusion:
The study successfully developed a predictive model capable of assessing an applicant’s creditworthiness based on socio-economic parameters. The findings emphasize the importance of income stability, education level, and family status in determining credit risk. The implementation of the random forest model enhanced prediction accuracy, making it a valuable tool for financial institutions to automate and improve credit card approval processes. Future work may focus on incorporating real-time data and post-COVID financial behaviors to enhance the model’s applicability in dynamic economic conditions.
