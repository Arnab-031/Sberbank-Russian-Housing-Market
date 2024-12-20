# Sberbank-Russian-Housing-Market
Sberbank, Russia’s largest bank, aims to predict real estate prices, offering stability for renters, developers, and lenders amid an uncertain economy. Russia’s volatile market and complex housing features, like bedrooms and location, pose unique challenges. This Kaggle competition tasks participants with building algorithms using diverse features, including housing data and macroeconomic trends, to improve price forecasting accuracy. By leveraging advanced models, Sberbank seeks to provide greater confidence to its customers in navigating unpredictable financial landscapes.

# Datasets
https://www.kaggle.com/c/sberbank-russian-housing-market/data

# Notebook 1: Sberbank_Pradictive modeling
# 1.	Objective:
•	Analysis of datasets for predictive modeling.
•	Implementation of regression methods, ensemble models, and performance optimization.
# 2.	Key Features:
•	Includes data preprocessing, handling of categorical variables using LabelEncoder.
•	Implements regression models with hyperparameter tuning.
•	Focus on ensemble learning techniques like stacking.
•	Reporting performance metrics on datasets.
# 3.	Technology Used:
•	Programming Language: Python.
•	Libraries: scikit-learn, pandas, numpy.
•	Machine learning algorithms: Decision Trees, Random Forest, SVM.
# 4.	Key Insights:
•	Ensemble predictions improve overall model accuracy.
•	Hyperparameter tuning ensures robust model performance.
•	Stacked model layer includes diverse algorithms for better predictions.


# Notebook 2: Sberbank_Feature_Selection_(BONUS)
# 1.	Objective:
•	Focuses on advanced feature selection methods for machine learning models.
•	Implements feature selection techniques such as:
•	SelectFromModel: A model-based ranking method.
•	SequentialFeatureSelector: Sequential forward search.
•	GeneticSelectionCV: Genetic algorithm for feature selection.
# 2.	Key Features:
•	Extensive use of scikit-learn for machine learning models.
•	Integration of vecstack and mlxtend libraries for stacking and feature selection.
•	Inclusion of cross-validation and hyperparameter tuning via GridSearchCV and RandomizedSearchCV.
# 3.	Technology Used:
•	Programming Language: Python.
•	Libraries: scikit-learn, imblearn, vecstack, mlxtend.
•	Tools for visualization and feature selection.
# 4.	Key Insights:
•	Comprehensive feature selection pipeline ensures model efficiency.
•	Use of stratified data subsets to manage computational overhead.
•	Incorporation of advanced algorithms for feature ranking and selection.

 # Combined Key Insights 
# 1.	Regression and Ensemble Learning:
•	Demonstrated improvement in model accuracy through stacking.
•	Variety of algorithms combined at stacking layer: Random Forest, Decision Tree, and SVM.
# 2.	Feature Selection:
•	Advanced selection methods enhance model interpretability and efficiency.
•	Use of stratified subsets reduces computational load while retaining feature diversity.
# 3.	Hyperparameter Tuning:
•	Cross-validation with GridSearchCV and RandomizedSearchCV optimizes model parameters.
# 4.	Reproducibility:
•	Comprehensive pipelines for data preprocessing, modeling, and evaluation.
•	Integration of both individual and stacked model predictions into Kaggle submissions.
