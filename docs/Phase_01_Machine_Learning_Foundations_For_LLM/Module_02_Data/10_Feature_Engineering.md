Feature engineering means creating, transforming, or selecting useful features from raw data so that a machine-learning model can learn better patterns.

Feature Engineering — Practical Example
Suppose we have this customer dataset:
| Customer | Age | Monthly Income | Total Spending | Months |
| -------- | --: | -------------: | -------------: | -----: |
| A        |  25 |        ₹30,000 |        ₹60,000 |     12 |
| B        |  40 |        ₹50,000 |      ₹1,20,000 |     24 |
| C        |  35 |        ₹40,000 |        ₹90,000 |     18 |

Step 1: Raw features
We already have:

Age
Monthly Income
Total Spending
Months

Step 2: Create new features
We can derive:
Annual Income

Annual Income = Monthly Income × 12

For customer A:

30,000 × 12 = ₹3,60,000

Average Monthly Spending

Average Monthly Spending = Total Spending ÷ Months

For customer A:

60,000 ÷ 12 = ₹5,000

Step 3: Final dataset
| Customer | Age | Monthly Income | Months | Annual Income | Avg Monthly Spending |
| -------- | --: | -------------: | -----: | ------------: | -------------------: |
| A        |  25 |        ₹30,000 |     12 |     ₹3,60,000 |               ₹5,000 |
| B        |  40 |        ₹50,000 |     24 |     ₹6,00,000 |               ₹5,000 |
| C        |  35 |        ₹40,000 |     18 |     ₹4,80,000 |               ₹5,000 |

Now the ML model has additional meaningful information that wasn't directly present in the original data.

REAL INDUSTRY FLOW

Raw Data
   ↓
Understand Features
   ↓
Create New Features
   ↓
Transform Features
   ↓
Select Important Features
   ↓
Final ML Dataset
   ↓
Train Model


FEATURE CREATION
Feature creation means creating a new feature from existing features to give the ML model more useful information.

Practical example
Suppose we have:

Monthly Income = ₹30,000
Months = 12
Total Spending = ₹60,000

We can create:
1. Annual Income
Annual Income = Monthly Income × 12
              = ₹30,000 × 12
              = ₹3,60,000
2. Average Monthly Spending
Average Monthly Spending = Total Spending ÷ Months
                         = ₹60,000 ÷ 12
                         = ₹5,000
3. Spending-to-Income Ratio
Spending Ratio = Monthly Spending ÷ Monthly Income

Simple industry example
For customer churn prediction:

Existing Features
       ↓
Monthly Charges
Tenure
Total Charges
       ↓
Feature Creation
       ↓
Average Monthly Charges
Customer Lifetime Value
Charges per Month
       ↓
ML Model
       ↓
Churn Prediction

FEATURE TRANSFORMATION
Feature transformation means changing the format or scale of existing features so that the ML model can use them more effectively.

Practical example: Scaling
Suppose our dataset has:
Age = 25
Salary = ₹50,000

The values are on very different scales:
Age     → 25
Salary  → 50000
A model such as KNN, K-Means, or Logistic Regression can be affected by this difference.
So we transform them into a common scale.

Min-Max Scaling
Formula:X_scaled = (X - X_min) / (X_max - X_min)
The values are converted approximately into:0 to 1

Other common transformations
1. Standardization:Converts values using mean and standard deviation.
Z = (X - Mean) / Standard Deviation
Usually produces values centered around 0.

2. Log Transformation:Useful when data is highly skewed.
Income → log(Income)

3. Normalization:Adjusts values to a common scale, depending on the normalization method.

Industry example
Raw Features
     ↓
Age: 25
Income: 50000
Spending: 120000
     ↓
Feature Transformation
     ↓
Scaled Age
Scaled Income
Scaled Spending
     ↓
ML Model

FEATURE ENCODING
Feature encoding means converting categorical (text) data into numerical values so that a machine-learning model can understand it.

Practical example
Suppose we have:
| Customer | Gender | Contract |
| -------- | ------ | -------- |
| A        | Male   | Monthly  |
| B        | Female | Yearly   |
| C        | Male   | Monthly  |
The ML model cannot directly work with "Male", "Female", "Monthly", etc.So we encode them.

1. Label Encoding
Example:Male   → 0
Female → 1
Useful when categories have a meaningful order or for suitable binary categories.

2. One-Hot Encoding
For:Contract = Monthly, Yearly, Two-Year
We create:
Monthly  Yearly  Two-Year
   1       0        0
   0       1        0
   0       0        1
   There is no artificial ordering between the categories.

Industry example
For a customer churn model:
Raw Data
   ↓
Gender = Female
Contract = Yearly
Payment = Credit Card
   ↓
Feature Encoding
   ↓
Gender_Female = 1
Contract_Yearly = 1
Payment_CreditCard = 1
   ↓
ML Model

FEATURE SELECTION
Feature Selection is the process of selecting the most relevant features from a dataset and removing irrelevant or redundant features before training a machine-learning model.

Customer Churn Prediction

Imagine a company wants to predict:

Will this customer leave the company?

This is our target variable:

Churn

The company has the following features:

Age
Tenure
Monthly Charges
Contract Type
Payment Method
Login Frequency
Support Tickets
Total Charges
Customer ID
Step 1 — Separate features and target
Features (X):
Age
Tenure
Monthly Charges
Contract Type
Payment Method
Login Frequency
Support Tickets
Total Charges
Customer ID


Target (y):
Churn
Step 2 — Examine the features

The ML engineer checks whether each feature provides useful information for predicting churn.

For example:

Customer ID

is mainly an identifier.

It doesn't describe the customer's behavior or characteristics in a meaningful way.

So we don't want to use it as a predictive feature.

Remove → Customer ID
Step 3 — Select useful features

After analysis, suppose the team determines that these features are useful:

Tenure
Monthly Charges
Contract Type
Payment Method
Login Frequency
Support Tickets
Total Charges

So instead of training the model with all available features:

9 features

we train it with:

7 selected features