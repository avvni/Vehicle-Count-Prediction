# Vehicle-Count-Prediction
The code predicts the vehicle count. We use the data collected by sensors at the road junction to train our model. It includes the number of vehicles at a certain time stamp. We clean and sort the data according to our needs. Using Regression for the numerical data in vehicles, Pandas for data manipulation and analysis, NumPy for arrays and Random Forest Regressor, which predicts the target by averaging the results of multiple decision trees, since we use Regression, i.e. a supervised learning technique used to predict a numerical value based on historical data. 
The model predicts approximately 9.88 vehicles at the specific timestamps. 
However, we evaluate the model's performance using Mean Squared Error. The MSE of the current model is larger than the baseline MSE for our given dataset. Implying a need for improvement in the model.
Lastly, upon tuning the model, we receive a 14.93% improvement over the baseline of MSE. 
