X Education Institute have some business problem. Institute wants to an application
model which can make prediction about hot lead to convert in customer. X education
wants to help them to find most promising lead.
In problem statement, Institute needs top factors to focus on to get more conversion.
This is classification type issue. We will use Classification logistic regression model. We
are going to assign lead score 0 to 100 on base of probability. Education has target lead
conversion rate to be around

We have proceeded assignment with very first step of load data and gather information about data. Problem is classification problem, so we used logistic regression to solve this problem. Problem comes under supervised learning. We divided assignment into phases.
Phase 1: Gather information about data
We collected data, inspect data at the level of get to know basic information about data. Purpose of assignment, requirement of business, type problem.
Phase 2: Inspection of data and infer information dataset
Read data to know any hidden pattern in data set. Size of dataset, how much missing values in datasets. In lead assignment, we found “select” value which have no meaning so must change in Nan.
Phase 3: Clean data / Wrangling data
We dropped columns which have more than 70% missing values, even columns also dropped which are not adding any information in model.
Some columns are having “select” value in columns, no sense of it in dataset so we have changed it in nan.
Phase 4: Handel outliers
Very few numerical columns have outlier. We analysis them and remove outliers.
Phase 5: Create dummy variables and Feature scaling
Convert all categorical variables into dummy variables.
Phase 6: Feature selections
Use RFE to select most relevant to predict target variable.
Phase 7: Split data in train & test and Model Preparation
Make model using logistic regression method. Make model perfect with select relevant feature in model. We do iteration to train model with best features. We removed and add features to select best fitted model. Check VIF to find multicollinearity and remove features which has very high multicollinearity.
