# Machine-learning-
In this reposit you can find different models built for a classification problem.

## Predict employee attrition:

# Procedures: 

## 1. Understanding the business problem. 

Employee Attrition is a huge problem across industries and generally costs the company a lot for
hiring, retraining, productivity and work loss for each employee who leaves. Price and Waters, a
boutique data science consulting firm, is looking to build a Machine Learning model to predict
whether an Employee might quit. Using this model, they might plan human intervention to alleviate
the issues faced by the employee. The firm is also interested in specific features that are highly
indicative of attrition.
The company in a pilot program, recorded employee data. The company collected employee
performance data for some of the months randomly for each employee to understand it in the context of attrition.
The company wants you to predict whether an employee would quit in the near future, given the data and to discover features
indicative of attrition.


## 2. Converting into a data science problem. 

What can be done here is , we can build classification model weather the employee will leave or not with the given demographs.

## 3. Exploring the data.(EDA)

Explorating the given data like  the columns given by visualising or by getting the summary stats of the data.

Packages used here for this visulaization are seaborn, matplotlib. 

## 4. Preprocessing of the data. 

Preprocessing includes removal of un-necessary columns, filling the missing data & converting the data into appropriate changes.

## 5. Feature engineering. 

Using the existing columns to create new columns. 


### Techniques 

Using SMOTE to over sample the training data since the target variable is highly class imbalanced. 

## 6. Model building & Evaluation.

F1 score is used as the evaluation metric, so that it can balance both the classess. 
