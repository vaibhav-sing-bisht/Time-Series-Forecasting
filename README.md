# Time-Series-Forecasting
Analyzed historical monthly sales data of a company. Created multiple forecast models for two different products of a particular Wine Estate and recommended the optimum forecasting model to predict monthly sales for the next 12 months along with appropriate lower and upper confidence limits
![image](https://user-images.githubusercontent.com/87828805/153257726-772d91c1-90ea-4802-8a28-661a5b237a4e.png)

## For Sparkling Dataset
![image](https://user-images.githubusercontent.com/87828805/153257819-8443d0df-dc70-4e81-8829-b63a845f332e.png)
•	The overall comparison of all the time-series forecast models are listed above table  in accordance with increasing RMSE against test data or in order of decreasing accuracy.

•	Triple exponential smoothing with alpha 0.4, Beta 0.1 and Gamma 0.2 performs to be the best model followed by manual SARIMA model. And lowest is performed by the Naïve model.
![image](https://user-images.githubusercontent.com/87828805/153257910-403358a0-f311-4d76-a6c5-490495477d21.png)
•	The best of SARIMA, Triple Exponential Smoothing and Moving Average models are plotted above against the test data.

•	The SARIMA and Triple Exponential Smoothing are found to be comparable in terms of performance and fitment with the test data.

## For Rose Dataset 
![image](https://user-images.githubusercontent.com/87828805/153258029-2316d924-168e-40f3-ad8e-bc29dd259237.png)
•	The overall comparison of all the time-series forecast models are listed below table 2.12 in accordance with increasing RMSE against test data or in order of decreasing accuracy.

•	Triple exponential smoothing with alpha 0.1, Beta 0.2 and Gamma 0.1 performs to be the best model followed by 2 point moving average model. And lowest is performed by the Naïve model.

![image](https://user-images.githubusercontent.com/87828805/153258096-af3c65ba-906c-4d67-9c47-4f7f9db4385c.png)

•	The best of SARIMA, Triple Exponential Smoothing and Moving Average models are plotted above against the test data.

•	2 point trailing moving average is found to be having the best fitment against the test data, through with lag of 2 and falling short at times.

•	Both SARIMA and Triple Exponential Smoothing are found a bit higher than actuals at any given point in time

### Line Plot for 12 month forecast on Sparkling dataset
![image](https://user-images.githubusercontent.com/87828805/153258410-91c3bd3a-aa4c-471e-878c-0537b1c21dd9.png)
![image](https://user-images.githubusercontent.com/87828805/153258458-0cb58405-30d1-4392-819c-6a96cb64aa14.png)
•	The model forecast sale of 29508 units of sparkling wine in 12 months into future which is an average sale of 2459 units per month.

•	The seasonal sale in December 1995 will hit a maximum of 6084 units before it drops to the lowest sale in January 1996 at 1215 units.

### Line Plot for 12 month forecast on Rose dataset

![image](https://user-images.githubusercontent.com/87828805/153258723-ea654b7d-71e3-401e-8769-ac4222e56ce3.png)
![image](https://user-images.githubusercontent.com/87828805/153258763-4a8e95a4-0562-4698-bf6e-1155d858829e.png)

•	The model forecast sale of 538 units of Rose wine in 12 months into future which is an average sale of 44 units per month.

•	The seasonal sale in December 1995 will hit a maximum of 82 units before it drops to the lowest sale in January 1996 at 24 units.






