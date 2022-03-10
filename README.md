# Project Goal
The goal of this project is to discover features that may be related to churn, and use these discoveries to create a machine learning classification model that can predict if a customer is about to churn or not.

***
# Project Description
Telco is an internet and phone company with a higher customer turn over than they'd like. Signing new customers up is a lot more expensive that keeping a customer, which is why most companies try so hard to keep thier customers from leaving. 

In this repository I will utilize a telecommunication company's (Telco) customer dataset to perform a very detailed Exploratory Data Analysis to develop a strong understanding of any patterns or trends existing in our data. Secondly, I will process the data and build a series of binary outcome classification models that will try to effectively predict whether a customer will or will not churn from the telecommunications platform.

***

# Project Planning
### Plan -> Acquire -> Prepare -> Explore -> Model & Evaluate -> Deliver

**Planning:**

Create a README file
Ensure accquire.py modules are well documents and functional.

**Acquisition:**

Obtain Telco data from Codeup mySQL database.

**Preparation:**

Clean Telco data from Codeup mySQL database.


**Exploration and Pre-processing:**

Ask and answer statistical questions about the Telco data
Visually represent findings with charts

**Modeling**

Split data appropriately
Use knowledge acquired from statistical questions to help choose a model
Create a predictions csv file from the best model

**Deliver**

Deliver a 5 minute presentation via a jupyter notebook walkthrough
Answer questions about my code, process, and findings

***

# Data Dictionary
Our dataset contains 7043 entries representing 7043 unique customers. There are 21 columns, with 19 features (target feature = 'Churn'). The features are numeric and categorical in nature, so we will need to address these differences before modeling.



**Classification labels**


Churn — Whether the customer churned or not (Yes or No)



**Customer services booked**
&nbsp;

PhoneService — Whether the customer has a phone service (Yes, No)

MultipleLines — Whether the customer has multiple lines (Yes, No, No phone service)

InternetService — Customer’s internet service provider (DSL, Fiber optic, No)

OnlineSecurity — Whether the customer has online security (Yes, No, No internet service)

OnlineBackup — Whether the customer has online backup (Yes, No, No internet service)

DeviceProtection — Whether the customer has device protection (Yes, No, No internet service)

TechSupport — Whether the customer has tech support (Yes, No, No internet service)

StreamingTV — Whether the customer has streaming TV (Yes, No, No internet service)

StreamingMovies — Whether the customer has streaming movies (Yes, No, No internet service)





**Customer account information**


Tenure — Number of months the customer has stayed with the company

Contract — The contract term of the customer (Month-to-month, One year, Two year)

PaperlessBilling — Whether the customer has paperless billing (Yes, No)

PaymentMethod — The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

MonthlyCharges — The amount charged to the customer monthly

TotalCharges — The total amount charged to the customer




**Customers demographic info**


customerID — Customer ID

Gender — Whether the customer is a male or a female

SeniorCitizen — Whether the customer is a senior citizen or not (1, 0)

Partner — Whether the customer has a partner or not (Yes, No)

Dependents — Whether the customer has dependents or not (Yes, No)


# Steps to Reproduce

1. Read this README.md

2. Download at the aquire.py and project_report.ipynb file into working directory

3. Create a .gitignore for .env file

4. Add your own env file to your directory with username, password, and host address.

5. Run the project_report.ipynb notebook


# Initial Questions for the Project

1. 
2.
3.
4.
5.


