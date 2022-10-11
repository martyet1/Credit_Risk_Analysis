# Credit_Risk_Analysis
module 17 challenge
# Overview
	_ the purpose of the assignment is to use different machine learning models and determine whether  	or not they are good to determine credit risk
## Results
	- balanced accuracy scores and precision and recall on six models
	- Naive Random Oversampling
		- imbalanced classification
		- Precision  .99
		- recall .59
		- f1 .73
	
	- SMOTE Oversampling
		- high precision (.99)
		- high recall (.69)
		- high f1 score (.81)

	- Undersampling
	- imbalanced classification report
		- precision .99
		- recall .40
		- f1 .69

	- combination of Over and Under sampling
		- precision .99
		- recall .57
		- f1 .72

	- Balanced Random Forest Classifier
		- precision .99
		- recall .89
		- f1 .93

	- Adaboost Classifier
		- precision .99
		- recall .89
		- f1 .63

	

### Summary
	- the Balanced Random Forest model does the best job of the six. The precision is almost perfect while still maintaining high recall. The model gets it right (precision) identifying credit risk while not sacrificing classifying all potential risks (recall). The harmonic means (f1) score is very high at .93
	- SMOTE Oversampling and Adaboost Classifier  are both good models but are not as accurate as Random Forest
	
