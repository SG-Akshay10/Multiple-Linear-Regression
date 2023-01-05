# Multiple-Linear-Regression

Multiple linear regression is used to estimate the relationship between two or more independent variables and one dependent variable. You can use multiple linear regression when you want to know:

* How strong the relationship is between two or more independent variables and one dependent variable.
* The value of the dependent variable at a certain value of the independent variables.

![image](https://user-images.githubusercontent.com/83088512/210696044-930cd291-a480-4cdd-89b6-9d09916a7578.png)<br/>
where,<br/>
* Y : the dependent or response variable<br/>
* B0 : this is the y-intercept.<br/>
* B1X1 : (B1) is the coefficient of the first independent variable (X1) in your model.<br/>
* e : this is the model error<br/>

Our basic agenda is to implement a multiple linear regression program using numpy and pandas and sklearn libraries.<br />
Then check the efficiency of the model using the following metrics :<br />

#### MEAN SQUARE ERROR : 

  ![image](https://user-images.githubusercontent.com/83088512/210354385-15589a5a-adfd-4940-97fb-171a41b4723a.png)

where,<br />
  * 𝑁 is the total number of observations (data points)<br />
  * yᵢ is the actual value of an observation and y^ is the predicted value<br />
  * J is the cost function which is the mean squared error in this case<br />
  
#### R-squared value:
  
  ![image](https://user-images.githubusercontent.com/83088512/210355039-e6a5fb91-3ae5-45f8-ab26-161f59f94590.png)

Where,<br />
  * yₚᵣₑ𝒹 is the predicted y value,<br />
  * y̅ is the mean, <br />
  * y is the actual value<br />
