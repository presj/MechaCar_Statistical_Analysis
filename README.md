MechaCar_Statistical_Analysis

Linear Regression to Predict MPG (Deliverable 1)

![Deliverable 1](https://user-images.githubusercontent.com/100803302/173189718-96203467-71d1-43b4-9373-e8ad10b88f33.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

According to our results, ground clearance and mpg (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. When an intercept is statistically significant, it means there are other variables and factors that contribute to the variation in quarter-mile time that have not been included in our model. These variables may or may not be within our dataset and may still need to be collected or observed.

Is the slope of the linear model considered to be zero? Why or why not?

From our linear regression model, the r-squared value is 0.68, which means that roughly 68% of all predictions will be correct when using this linear model. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The p-value of our linear regression analysis is 6.712e-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can say there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

Summary Statistics on Suspension Coils (Deliverable 2)

![total_summary](https://user-images.githubusercontent.com/100803302/173189821-aa123613-d58a-4930-b634-ecc018683bd9.png)

![lot_summary](https://user-images.githubusercontent.com/100803302/173189825-dadafac4-15e0-4301-b710-6da027f47fb2.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Using our visualization in combination with our calculated p-value and r-squared value, we have determined there is a significant relationship between ground_clearance and mpg. R-squared:  0.7119,	Adjusted R-squared:  0.6791 suggest a strong correlation and the P-value lower than 0.05, suggest strong correlation and prediction as expalined in more detail in Deliverable 1. PSi distribution is normal since P-value is way less than 0.05. Our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.
