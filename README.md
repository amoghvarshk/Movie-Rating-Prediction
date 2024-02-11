# Movie-Rating-Prediction
This project focuses on predicting IMDB scores of movies based on various features such as gross revenue, budget, release year, and content rating. The dataset includes information on movie titles, gross revenue, budget, release year, duration, genre, and content rating. The predictive models are built using linear regression techniques, and different model specifications are compared for their predictive performance.

Data Cleaning
The dataset is cleaned to remove missing values and irrelevant features. Numeric variables are scaled, and categorical variables are transformed to facilitate modeling.

Linear Regression Models
Three linear regression models are constructed to predict IMDB scores:

Model 1: Predicts IMDB scores using gross revenue, release year, and budget.
Model 2: Extends Model 1 by including content rating as a predictor.
Model 3: Incorporates an interaction effect between gross revenue and content rating.
Prediction and Model Evaluation
Models are evaluated using a validation dataset, and their performance is compared based on root mean squared error (RMSE) and mean absolute error (MAE). The goal is to identify the model with the best predictive performance for IMDB scores.
