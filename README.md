# Ecommerce-Product-Categorization
## Problem Statement
### Nowadays, for product purchase and selling, we have a lot of ecommerce sites. It helps us to do the transaction through online and reduce our time with travel and allow us to see all the products across the multiple stores. To help users to see the relevant info we want to categorize the products based on the product description.

## About Dataset
### Ecommerce dataset has 14999 rows and 15 columns of product_id, product_name, product_url, discount_price, product_rating, product_description, product_category_tree and few more. 

###     Input Feature => description
###     Output Feature => product_category_tree

## Exploratory Data Analysis

### Let’s see insights of data. The target product_category_tree has totally 11 distinct values. Those are Clothing, Footwear,Jewellery, Watches, and few more. We have product description of max length 2000+. It contains alphabets, numbers and lot of special characters. We should remove it before applying the ML model.

## Machiner Learning Models Deployed

###  Logistic Regression Classifier
###      Accuracy_score 	= nn
###      F1-Ration		= nn
###  Support Vector Machine Classifier.
###      Accuracy_score 	= nn
###      F1-Ration		= nn
###  Random Forest Classifier (ensemble model).
###      Accuracy_score 	= nn
###      F1-Ration		= nn

