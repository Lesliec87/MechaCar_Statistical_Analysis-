# MechaCar_Statistical_Analysis-

## Linear Regression to Predict MPG

![image](https://github.com/Lesliec87/MechaCar_Statistical_Analysis-/blob/main/summary_mecha.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero? Why or why not?
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. 
- The ground_clearance and vehicle_length  were the two variables that had a random amount of variance. 

- Since the p-value is less than 0.05 it seems that it will not be considered to be zero. 

- Since the R-squared value is 71%, the model will predict mpg values effectively since this is means that that will be the percentage of the model predictions to be correct. 

## Summary Statistics on Suspension Coils

![total summary](https://github.com/Lesliec87/MechaCar_Statistical_Analysis-/blob/main/total_summary.png)

![lot summary](https://github.com/Lesliec87/MechaCar_Statistical_Analysis-/blob/main/lot_summary.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- For Lot 1 and Lot 2 they did not exceed 100 pounds per square inch and both variances are withing the design specification around 1500 for the mean and medium.
- For Lot 3 this did exceed 100 pounds per square inch which the variance is outside of the design specificaiton.

## T-Tests on Suspension Coils

- Lot 1 the PSI value is 1
- Lot 2 the PSI values is 0.6072
- Lot 3 the PSI value is  0.04168 

![t.test](https://github.com/Lesliec87/MechaCar_Statistical_Analysis-/blob/main/t.tests.png)

## Study Design: MechaCar vs Competition

What metric or metrics are you going to test?
- Mpg and PSI 

What is the null hypothesis or alternative hypothesis?
- Null hypothesis since there was no statistical difference between the competition's mpg dataset and MechaCar's mpg dataset.

What statistical test would you use to test the hypothesis? And why?
- We implemented the t.test for this analysis and would be the best to approach an analysis with the competitors. 

What data is needed to run the statistical test?
- We would need to confirm that it is less than 0.05 since this is typically considered to be statistically significant, for us to know if the null hypothesis should be rejected.
