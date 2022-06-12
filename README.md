MechaCar_Statistical_Analysis

Linear Regression to Predict MPG (Deliverable 1)

![Deliverable 1](https://user-images.githubusercontent.com/100803302/173189718-96203467-71d1-43b4-9373-e8ad10b88f33.png)
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Ground clearance, mpg, and intercept are statistically unlikely to provide random amounts of variance to the linear model. When an intercept is statistically significant, it means there are other variables and factors that contribute to the variation in quarter-mile time that have not been included in our model. These variables may or may not be within our dataset and may still need to be collected or observed.

Is the slope of the linear model considered to be zero? Why or why not?

The r-squared value is 0.68, meaning roughly 68% of all predictions will be correct when using this linear model. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The p-value of our linear regression analysis is 6.712e-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can say there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

Summary Statistics on Suspension Coils (Deliverable 2)
![total_summary](https://user-images.githubusercontent.com/100803302/173189821-aa123613-d58a-4930-b634-ecc018683bd9.png)
![lot_summary](https://user-images.githubusercontent.com/100803302/173189825-dadafac4-15e0-4301-b710-6da027f47fb2.png)
The current manufacturing data meets this design specification for all manufacturing lots in total. Individually, lots 1 and 2 meet the specification, but lot 3 does not.

T-Tests on Suspension Coils (Deliverable 3)
![Deliverable 3](https://user-images.githubusercontent.com/100803302/173207453-9f39dc95-fb4f-4f35-911d-f578534faa06.png)
When looking at the entire population of the production lot, the variance of the coils is within the 100 PSI variance requirement.

Study Design: MechaCar vs Competition (Deliverable 4)

One study to quantify how well the MechaCar performs against the competition might make the following considerations:

What metric or metrics are you going to test?  

Three attributes car shoppers look for in a new vehicle purchase are horsepower, mpg, and connectivity; we can include these metrics in our study.

What is the null hypothesis or alternative hypothesis? 

Our null hypothesis is that the MechaCar does not outperform its competitors (of the same car class) with more horsepower, mpg, and technology features.

What statistical test would you use to test the hypothesis? And why?  

A one-way ANOVA could be used because it best tests the means of a single dependent variable across a single independent variable with multiple groups. 

What data is needed to run the statistical test?  Needed data includes vehicle manufacturer, model, class, cost, and engine size.

