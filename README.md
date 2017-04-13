# This is a demo to show how to transform the data with weigh of evidence (WOE) to increase the predictive model.
The dataset if "GermanCredit" from the "caret" R package. It has 1000 observations. The dependent variable is CLASS with two levels. CLASS = 1 represents a good credit, and CLASS = 0 represents a bad credit. Two of the 59 predictors only have one leve, "Purpose.Vacation" and "Personal.Female.Single", and they are excluded in this analysis. Out of the 57 predictors, 53 of them only have two levels. The goal is to use logistic regression to predict the probability of CLASS = 1.

The original data is transformed with its weight of evidence (WOE). The result of the regression shows that this transformation improve the model by decreasing the type-I error by 3.5%.
