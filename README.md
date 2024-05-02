# Python-Implementation-of-Linear-Regression-Line


According to Body Mass Index (BMI) The average weights of healthy body for the corresponding heights was given in the following table. The aim was to find a linear regression line for the relationship between height and weight, and correlation coefficient for the relationship. So I create two list h and w for the data that was given. I then found a python function to find the line of best fit. I will find m and b such that where m is slope and b is y-intercept of the line in  y = mx + b. I will the draw a scatter plot of data and line of best fit in the same figure. To use the function that I'd created to find the correlation coefficient. Then I found the accuracy of my model according to the correlation coefficient and found the average weight when the height is 70 inches in my model. Compare the result with the actual weight given in the data.





![Screenshot (107)](https://github.com/deonjr04/Python-Implementation-of-Linear-Regression-Line/assets/146729697/2f6961b8-980c-473a-a7df-8cf6557bc4fb)

![Screenshot (106)](https://github.com/deonjr04/Python-Implementation-of-Linear-Regression-Line/assets/146729697/fe36d604-b69b-416f-8412-86006c86b62f)




# The Model And Discussion On Accuricy Of The Model
When I apply line of best fit function (bestFitLine()) the model is

w = 4.024h - 132.22

where h is the height of health body and w is corresponding weight of the body.

And, when I'd apply correlation coeffcient function (corrCoefficient()) I found the correlation coeffcient which is

r=0.9997

That is very close to 1. Which means the model is very strong, almost perfect and positive.


![Screenshot (105)](https://github.com/deonjr04/Python-Implementation-of-Linear-Regression-Line/assets/146729697/882d576d-8a07-4697-9108-1ecff2d94f55)

# The accuracy of the model in the scatter plot
As it is seen in the scatter plot above the model that I found is acurate. So the predicted weight in model is 149.46 which is very closed to actual weight. I found the percenttage of the difference of actual and predicted weight, it is 0.31 %, which is enough small. Thus, I can take the weight from te model as actual weights.






