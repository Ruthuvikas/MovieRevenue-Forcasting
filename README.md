# Movie Revenue Forcasting
Predicting box office success of movies. 

Predict the revenue generated by the movie based on parameters such as vote_count, budget, vote_avg.

Machine learning models:

OLS regression
Decision tree
Random Forest
Catboost
XGboost

Results:


<img width="334" alt="Screenshot 2023-12-13 at 1 25 50 PM" src="https://github.com/Ruthuvikas/STA-221/assets/43813488/fe079a0b-c88e-49a6-b8b5-29fdc7448e67">


The comparative performance of various predictive models was evaluated based on their R2 score
and Mean Square Error (MSE). Table 1 presents the summary of these evaluations.

From the results, it is evident that the Random Forest model outperformed other models with the
highest R2 score of 0.74, indicating a strong correlation between the predicted and observed values.
Additionally, it achieved the lowest MSE of 0.27, suggesting a superior prediction accuracy with
minimal error.

The CatBoost and XGBoost models also showed commendable performance, with R2 scores of
0.73 and 0.72, respectively, and relatively low MSE values of 0.29 and 0.31. These results suggest
that ensemble methods, particularly those that implement boosting and bagging techniques, tend to
provide more accurate and reliable predictions in our dataset.

The OLS Regression model showed moderate predictive power with an R2 score of 0.68 and an
MSE of 0.34. While it was outperformed by the ensemble methods, it still holds relevance due to its
simplicity and interpretability in certain contexts.

The Decision Tree model had the lowest R2 score of 0.62 and the highest MSE of 0.41. This could
be attributed to its tendency to overfit the training data, leading to lower performance on the test set.
In conclusion, the ensemble methods, particularly Random Forest, demonstrated superior predictive
accuracy in our analysis. However, the choice of the model should also consider the specific
requirements and constraints of the application, such as the need for model interpretability and computational
efficiency.


