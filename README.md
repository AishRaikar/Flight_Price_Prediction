# Flight_Price_Prediction
Flight Price Prediction Using Machine Learning

This project involves the analysis of a comprehensive flight booking dataset obtained from a popular flight booking website, comprising over 300,000 data points. The primary objective is to predict future flight prices by employing a combination of exploratory data analysis (EDA), statistical methods, and machine learning algorithms. The insights gained from this analysis can be pivotal for both travelers and the aviation industry.

Linear Regression Model:
R2 Score: 0.905
Mean Absolute Error (MAE): 4625
Mean Absolute Percentage Error (MAPE): 0.435%
Mean Square Error (MSE): 49200540
Root Mean Squared Error (RMSE): 7014
The Linear Regression model provides a solid foundation for predicting flight prices, with an R2 score of 0.905 indicating a high level of accuracy. However, the model's MAPE and RMSE suggest some room for improvement.

Decision Tree Regressor Model:

R2 Score: 0.976
MAE: 1175
MAPE: 0.074%
MSE: 12618384
RMSE: 3564
The Decision Tree Regressor outperforms Linear Regression, with a significantly lower MAE and MAPE. The model's R2 score of 0.976 indicates a robust predictive capability, making it a promising choice for flight price prediction.

Random Forest Regressor Model:

R2 Score: 0.985
MAE: 1091
MAPE: 0.070%
MSE: 7768849
RMSE: 2787
The Random Forest Regressor emerges as the top-performing model among the three, showcasing superior accuracy with an R2 score of 0.985. Its MAPE and RMSE values are notably lower than those of Linear Regression and Decision Tree models, signifying its effectiveness in predicting flight ticket prices.

Conclusion:
Based on the comprehensive evaluation of these models, the Random Forest Regressor stands out as the most reliable choice for predicting flight ticket prices. Its exceptional performance, as reflected in the high R2 score and low error metrics, makes it the preferred model for deployment in real-world scenarios.

This GitHub repository serves as a valuable resource for understanding the data analysis process, model evaluation, and the implementation of machine learning algorithms for predicting flight prices. Users can explore the Jupyter notebooks, datasets, and codebase to gain insights into the methodologies employed and replicate the analysis for similar datasets. Feel free to contribute, provide feedback, or use the models for your flight price prediction applications.
