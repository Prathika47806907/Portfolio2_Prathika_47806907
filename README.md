## Portfolio2_Prathika_47806907
portfolio_2_Prathika_47806907

## Objective
The goal of the second analysis task is to train linear regression models to predict users' ratings towards items. This involves a standard Data Science workflow: exploring data, building models, making predictions, and evaluating results. In this task, we will explore the impacts of feature selections and different sizes of training/testing data on the model performance. We will use another cleaned combined e-commerce sub-dataset that **is different from** the one in “Analysis of an E-commerce Dataset” task 1.
After this random split the data into training and testing sets with different sizes:
    * Case 1: training data containing 10% of the entire data;
    * Case 2: training data containing 90% of the entire data.
* Print the shape of training and testing sets in the two cases.

## My Analysis
The correlation coefficients between the rating and helpfulness, gender, category, and review columns are -0.0075, -0.0343, -0.1632, and -0.0361, respectively. A correlation coefficient of **0** indicates **no correlation**, a **positive correlation** coefficient indicates a positive relationship between the two variables that is **1**, and a **negative correlation** coefficient indicates a negative relationship between the two variables that is **-1**.

In this case, all of the correlation coefficients are  **weak**, indicating that there is no strong relationship between the rating and any of the other variables. The only exception is the correlation between the rating and the helpfulness column, which is slightly negative. This suggests that there is a slight inverse relationship between the two variables, meaning that reviews that are rated higher are also less likely to be helpful.

## Conclusion
^Theis Portfolio indicates that the model trained with the most correlated features and more training data has the lowest RMSE and MSE scores.
^Comparing these four graphs,the Model A have the low RMSE and MSE scores where it is first mostly co-related.
^The Model-C is less trained and has strong MSE and RMSE Values.
^The results show that the training data size and feature selection have a significant impact on the model performance. Model-c, which has a larger training data size and uses the most correlated features, performs the best. Model-a, which has a smaller training data size but still uses the most correlated features, performs slightly worse than Model-c. Model-d, which has a larger training data size but uses the least correlated features, performs the worst.
^The larger training data size allows the model to learn more about the underlying relationships between the features and the ^target variable. 
The most correlated features are those that are most related to the target variable. Using these features helps the model to make more accurate predictions.
^Overall, the results of this analysis suggest that the training data size and feature selection are important factors that should be considered when building a machine learning model. By using a large training data size and the most correlated features, it is possible to build a model that can make accurate predictions.
