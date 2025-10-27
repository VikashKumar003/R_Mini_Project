# R_Mini_Project
An R-based machine learning project that predicts whether a movie is a Hit or Flop using TMDB data, applying and comparing Decision Tree and Logistic Regression models.

TITLE : Movie Success Prediction using Decision Tree and Logistic Regression

I) Project Overview

This mini project focuses on predicting whether a movie will be a Hit or Flop based on its attributes using machine learning algorithms in R.
Two models — Decision Tree (DT) and Logistic Regression (LR) — were developed and compared to analyze performance and interpretability.

II) Dataset Information

⦁	Dataset Name: tmdb_5000_movies.csv and tmdb_5000_credits.csv
⦁	Source: The Movie Database (TMDB)
⦁	Number of Records: 5000+ movies
⦁	Selected Features:
	budget – Movie production cost
	revenue – Total box office revenue
	popularity – Popularity score
	runtime – Movie duration (minutes)
	vote_average – Average IMDb-like rating
	vote_count – Number of audience votes
	Target Variable: Success (Categorized as Hit or Flop)

III) Technologies and Packages Used

⦁	Language: R
⦁	IDE: RStudio
⦁	Libraries:
	dplyr – Data preprocessing and manipulation
	caret – Model training, evaluation, and confusion matrix
	rpart – Decision Tree modeling
	rpart.plot – Tree visualization
	pROC – ROC curve and AUC calculation
	ggplot2 – Accuracy comparison visualization

IV) Model Building

1. Decision Tree Model

⦁	Built using rpart() function with Success as the target variable.
⦁	Visualized using rpart.plot().
⦁	Provided interpretable rules showing relationships between features and outcomes.
⦁	Achieved accuracy of 93.64%.

2. Logistic Regression Model

⦁	Built using glm() with family = binomial.
⦁	Predicts probability of success (Hit or Flop).
⦁	Evaluated using confusion matrix and ROC curve.
⦁	Achieved accuracy of 99.38%.

V) Conclusion

⦁	Both models effectively predict movie success using TMDB data.
⦁	Logistic Regression achieved higher accuracy, while the Decision Tree provided visual insights.
⦁	Key predictors: revenue, budget, and vote_average.
⦁	The project demonstrates how data-driven analysis can assist the film industry in forecasting success and making informed production decisions.

VI) How to Run the Project

1.	Open RStudio.
2.	Set your working directory:
	setwd("C:/Users/HP/OneDrive/Documents/R_Programming")
3.	Install required packages:
	install.packages(c("dplyr", "caret", "rpart", "rpart.plot", "pROC", "ggplot2"))
4.	Load and run the R script step-by-step.
5.	View outputs such as:
	Decision Tree Plot
	Confusion Matrix
	ROC Curves
	Model Accuracy Comparison Bar Chart


