This is a typical House Price prediction project that is available in Kaggle and my first project
This project used linear regression to predict house prices using 10+ features. 
Original Training R²: 0.638 & 0.674 on Training and Test data respectively
After analysis of sales price across various classes, identified that the issue was the prediction of expensive houses
Most important features were GrLivArea, OverallQual, and NeighborhoodBand which were added one at a time
I finally added all of them since they all gave a good boost to the R2 and the MSE was the least for the final model
Final R²: 0.739 and 0.776, indicating strong model fit.
