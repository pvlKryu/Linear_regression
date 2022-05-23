# Linear_regression
A small program to implement multiple linear regression with Sklearn library and on my own.
<br>
## Input data:
For this example I used a data set on the cost of houses for 1500 rows
![image](https://user-images.githubusercontent.com/57821178/169805017-284aae59-4a6c-44e9-95db-a8103e912006.png)<br>
![image](https://user-images.githubusercontent.com/57821178/169806779-e6fcfe31-50ad-4f39-a343-d564ee532ac9.png)
### Columns: <br>
![image](https://user-images.githubusercontent.com/57821178/169805449-1bf48b8d-ced7-4a66-8a10-2356012844fc.png) <br>
![image](https://user-images.githubusercontent.com/57821178/169805485-06fc9f13-da78-4ef2-86d5-e4909f7362f8.png)<br>
![image](https://user-images.githubusercontent.com/57821178/169805590-64af58f8-e787-443f-ada1-baf0f1e22e80.png) <br>
![image](https://user-images.githubusercontent.com/57821178/169805716-3b0354f6-470f-419c-a39d-325eb67b2196.png) <br>
## Data processing:
- One-hot encoding for categorial features
- Divide the sample randomly into train and test data (test - 25% of the data)
- Fill nan - in numerical features from the sample train
- Standard scaling by Train sample
## Results:
### sklearn:
Train mse:
19306.85068414516 <br>
Test mse:
3.3287891454200028e+16
### Self-written gradient descent:
Train MSE GD_Regressor:  197151.96183913611 <br>
Test MSE GD_Regressor:  198865.79451044145
