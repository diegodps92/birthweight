# Birthweight
Regression Analysis that helps to predict the birthweight based on demographic and pre natal control information. With featuring engineering trying to figure out what are the best modified features that can help to improve the R square. 

In addition I used different types of model to improve the difference between the score of the training and test data:
- OLS Model
- Lasso Model
- ARD Model
- KNN Model

Finally those are my final results, choosing at the end the Lasso Model because of the difference between Test and Train Score.

Model                          Train Score      Test Score      GAP Score
-----                          -----------      ----------      ----------
OLS                            0.746            0.709           0.037
Lasso  (Final Model)           0.745            0.713           0.032
ARD                            0.744            0.71            0.034
KNN Regression                 0.704            0.586           0.118
