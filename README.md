# Linear-Regression

INTRO to LIN-REG:
-----

The Linear regression analysis is the most used of all statistical techniques and it is the first and foremost concept that we learn and practice in our way to conquer advanced machine learning techniques.

>*#For people new to the word __"Regression"__:
>*__Regression__*is the art and science of fitting a straight line to pattern of data points.

In linear regression model the *__'variable of interest'__*, commonly knows as *__'dependent variable'__* is predicted from *__k__* other variables called as *__'independent variables'__* using a __linear equation__. If __Y__ denotes the variable of interest (the so-called dependent variable) and __X1, …, Xk,__ are the independent variables, the assumption is that the value of __Y__ at time __t__ (or row __t__) in the data sample is determined by the linear equation: 

![](/images/Lin-Reg-equation.PNG)

where 
- __β__ s are the constants
- __epsilons__ are independent and identically distributed (i.i.d.)
normal random variables with mean zero (the “noise” in the system).
- __β0__ is the __intercept of the model__ —the expected value of __Y__ when all the __X’s__ are zero
- __βi__ is the coefficient (multiplier) of the variable Xi 

The __β__ s together with the __mean and standard deviation of the epsilons__ are the __*parameters*__ of the model. 

The corresponding equation for *predicting __Yt__ from the corresponding values of the __X’s__ is therefore*


