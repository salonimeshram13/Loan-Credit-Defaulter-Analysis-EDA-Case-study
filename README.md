# Loan-Credit-Defaulter-Analysis-EDA-Case-study
![Screenshot 2023-11-01 145016](https://github.com/salonimeshram13/Loan-Credit-Defaulter-Analysis-EDA-Case-study/assets/136232688/32b38f69-2955-46ee-9fda-06059f5c8e35)

## Business Understanding
A consumer finance company specialises in providing various types of loans to urban customers. When the company receives a loan application, it has to decide whether to approve or reject it based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
- If the applicant is not likely to repay the loan, i.e., they are likely to default, then approving the loan may lead to financial loss for the company.

## Data Analysis approach
We have to analyze the data to identify the driving factors • To start with the data analysis, the data set had to be cleaned and prepared for the analysis, then analyzed and visualized. • Clean the dataset using appropriate methods • Once the data set was cleaned, univariate, bivariate and mulitvariate analysis need to be done • Visualization techniques were used to draw charts and graphs and then meaningful insights from them.

## Data Understanding
- The data is collected from a company which is the largest online loan marketplace facilitating personal loans, business loans, and the financing of medical procedures. 
- The dataset contains information about past loan applicants and whether they ‘defaulted’.  
- It contains the complete loan data for all loans issued from 2007 to 2011.
- There are 39717 rows and 111 columns in total.
- The analysis is mainly done on the information like loan amount, term length, interest rate, annual income, installment, employee title, employee length, issue date, purpose, total payment, total received interest and the target variable “Loan Status”.

## Analysis
Univariate Analysis, Segmented Univariate Analysis, Bivariate Analysis, Multivariate Analysis. <br>
After plotting some visualizations, we were able to get some meaningful insights

## Model Building
Created a machine learning model to check if the applicant will turn out to be defaulter or not.<br> 
The model turn out to be 86.62% accurate.


![Screenshot 2023-11-01 142658](https://github.com/salonimeshram13/Loan-Credit-Defaulter-Analysis-EDA-Case-study/assets/136232688/e43b519d-590e-4f8f-8f12-bc958965e102)



![Screenshot 2023-11-01 142832](https://github.com/salonimeshram13/Loan-Credit-Defaulter-Analysis-EDA-Case-study/assets/136232688/e016dedb-84d3-42c5-adce-518baf467d48)

## Libraries used
Pandas & Numpy were used for analysis.<br>
Seaborn, Matplotlib, Plotly, graph_objs used for visualizations.<br>
