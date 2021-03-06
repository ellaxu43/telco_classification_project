# Project Goal
The goal of this project is to discover features that may be related to churn, and use these discoveries to create a machine learning classification model that can predict if a customer is about to churn or not.

***
# Project Description
&nbsp;
&nbsp;
&nbsp;
Telco is an internet and phone company with a higher customer turn over than they'd like. Signing new customers up is a lot more expensive that keeping a customer, which is why most companies try so hard to keep thier customers from leaving. 

In this repository I will utilize a telecommunication company's (Telco) customer dataset to perform a very detailed Exploratory Data Analysis to develop a strong understanding of any patterns or trends existing in our data. Secondly, I will process the data and build a series of binary outcome classification models that will try to effectively predict whether a customer will or will not churn from the telecommunications platform.

***

# Project Planning
&nbsp;
&nbsp;
&nbsp;
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
&nbsp;
&nbsp;
&nbsp;

Our dataset contains 7043 entries representing 7043 unique customers. There are 21 columns, with 19 features (target feature = 'Churn'). The features are numeric and categorical in nature, so we will need to address these differences before modeling.



**Classification labels**
&nbsp;
&nbsp;
&nbsp;

Churn ??? Whether the customer churned or not (Yes or No)



**Customer services booked**
&nbsp;
&nbsp;
&nbsp;
PhoneService ??? Whether the customer has a phone service (Yes, No)

MultipleLines ??? Whether the customer has multiple lines (Yes, No, No phone service)

InternetService ??? Customer???s internet service provider (DSL, Fiber optic, No)

OnlineSecurity ??? Whether the customer has online security (Yes, No, No internet service)

OnlineBackup ??? Whether the customer has online backup (Yes, No, No internet service)

DeviceProtection ??? Whether the customer has device protection (Yes, No, No internet service)

TechSupport ??? Whether the customer has tech support (Yes, No, No internet service)

StreamingTV ??? Whether the customer has streaming TV (Yes, No, No internet service)

StreamingMovies ??? Whether the customer has streaming movies (Yes, No, No internet service)





**Customer account information**
&nbsp;
&nbsp;
&nbsp;

Tenure ??? Number of months the customer has stayed with the company

Contract ??? The contract term of the customer (Month-to-month, One year, Two year)

PaperlessBilling ??? Whether the customer has paperless billing (Yes, No)

PaymentMethod ??? The customer???s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

MonthlyCharges ??? The amount charged to the customer monthly

TotalCharges ??? The total amount charged to the customer




**Customers demographic info**
&nbsp;
&nbsp;
&nbsp;

customerID ??? Customer ID

Gender ??? Whether the customer is a male or a female

SeniorCitizen ??? Whether the customer is a senior citizen or not (1, 0)

Partner ??? Whether the customer has a partner or not (Yes, No)

Dependents ??? Whether the customer has dependents or not (Yes, No)
***

# Steps to Reproduce
&nbsp;
&nbsp;
&nbsp;
1. Read this README.md

2. Download at the aquire.py and project_report.ipynb file into working directory

3. Create a .gitignore for .env file

4. Add your own env file to your directory with username, password, and host address.

5. Run the project_report.ipynb notebook

***

# Initial Questions for the Project
&nbsp;
&nbsp;
&nbsp;
1. Are customers who pay manually more likely to churn than customers who pay automatically?

2. Are customers with Fiber internet has different churn rate compare to customers with DSL?

3. Do customers who churn have a higher average monthly spend than those who don't?

4. Are customer with Fiber internet has higher monthly charges than customers with DSL? 

***

# Modeling
&nbsp;
&nbsp;
&nbsp;

1. Train model

2. Make predictions

3. Evaluate model

4. Compute accuracy


# Recommendations 
&nbsp;
&nbsp;
&nbsp;
1. Reduce monthly price espicially for fiber optic internet service


2. Promot customer to opt-in auto pay by offer a small discount.



# Next Steps
&nbsp;
&nbsp;
&nbsp;

1. Need more time to investigate the fiber optic inernet services, the service quality, cause of the higher price.... etc.


