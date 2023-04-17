# Telcom Churn Analysis by Nora Dong
## Topic 
The project is about analyzing customer churn behavior in a telecommunication firm using Python. 

## Research motivation and framework
This research aims to fill the gap of research in Telecom customer retention strategies with a novel churn analysis framework. The code is attached to a research paper by the author. Based on the existing knowledge and research gap in telecom churn analysis, the paper introduces the framework which combines churn prediction and customer segmentation. Then four machine learning models are trained, assessed and implemented to predict the churn, and to select important contributors based on the best-performed model. In customer segmentation analysis, the paper will first use a naive method to group the customers by different churn probabilities; K-means clustering will further segment customers who are more likely to churn and the churn contributors will be fed into customer segments. Last, the paper provides managerial insights and recommendations based on specific characteristics in different segments. Future research directions and limitations are also discussed. 

## Version Info
The original code is completed in December 2021, and the code is revised on April 17, 2023.

## Content of the coding

### I. Introduction
- Motivation and Design
- Dataset

### II. Data Pre-processing
- Prepare data and packages
- Data cleaning and transformation 

### III. Exploratory data analysis (EDA)
- Churn (dependent variable)
- Customer demographics and account features 

### IV. Churn Prediction (Supervised Machine Learning)
- Model preparation
 - Cross validation 
 - Class balancing
- Model fitting
 - Adaboost
 - Decision Tree
 - Logistic Regression
 - Random Forest
- Model evaluation
 - Performance metrics
 - ROC and refit time curve
 - Confusion matrix
 - Classification report 

### V. Factorial Analysis
- Adaboost's Important Variables
- Decision Tree's Plot

### VI. Customer Segmentation
- Naive method
- K-means clustering

### VII. Conclusion and Discussion
