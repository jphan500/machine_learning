# About
This repository contains two python notebooks related to the prediction of car prices and heart disease.  

The first notebook uses linear regression using the pandas and scikit learn library to explore and predict car prices using singular and multiple linear regression. It uses a variety of input variables including wheelbase,	carlength, carwidth, carheight,	curbweight,	enginesize,	boreratio,	stroke,	compressionratio,	horsepower,	peakrpm,	citympg and	highwaympg to predict the price. Cross fold validation, rmse and rsquared values are used to validate the final prediction.  

Conclusion: In the end, horsepower was one of the strongest indicators related to price. And for every 1 unit increase in horsepower, the price was expected to go up by an average of $163. Predictions were about $3,900 away from the actual price.

The second notebook uses logistic regression using the pandas and scikit learn library to explore and classify individuals as either having heart disease or not based on several metrics related to health and physical habits. Variables include BMI,	Smoking,	AlcoholDrinking,	Stroke,	PhysicalHealth,	MentalHealth,	DiffWalking,	Sex,	AgeCategory,	Race,	Diabetic,	PhysicalActivity,	GenHealth,	SleepTime,	Asthma,	KidneyDisease and	SkinCancer. ROC, AUC, precision, recall, f1-score, and support were used too validate the final prediction.  

Conclusion: Age, prior incidents and general health status were the strongest indicators.
