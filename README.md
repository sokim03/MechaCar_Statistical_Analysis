# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/96352427/163791813-9a636bb7-b6fc-4f9a-950d-c38e095bd82d.png)

Variables vehicle_length and ground_clearance provide a non-random amount of variance to the mpg values due to their low p-values.
The slope of the linear model is not considered to be zero because all the coeffiecient estimates are not zero.
The linear model predicts mpg of MechaCar prototypes effectively because the multiple R-Squared value shows that 71.49% predictions can be determined.

## Summary Statistics on Suspension Coils
![image](https://user-images.githubusercontent.com/96352427/163797125-5d45027e-21d4-4fd9-8ac5-cd7ccba709ac.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
For lots 1 and 2, these meet the specifications for suspension coils with a variance below 100. However, lot 3 shows a variance at 170 indicating it does not meet the specifications for the MechaCar suspension coils. 

## T-Tests on Suspension Coils
![image](https://user-images.githubusercontent.com/96352427/163797998-7b80c784-2d58-46e0-8abc-2c0d45321f14.png)

The p-value across all manufacturing lots showed a value of 0.06 indicating that it's over the p-value 0.05. The confidence interval at 95% also shows it being between 1497-1500 showing that the null hypothesis is acceptable. Individually, for lots 1 and 2, also showed p-values over 0.05 and confidence intervals at 95% between 1499-1500 showing that the PSI mean is not significantly different from the 1500 mean. However, lot 3 shows a p-value under 0.05 with a 95% confidence interval between 1492-1500 showing a PSI mean at 1496, indicating differences between the 1500 mean value and that the null hypothesis should be rejected. 

## Study Design: MechaCar vs Competition
To quantify how the MechaCar vs Competition could be measured is the cost between the two.
The null hypothesis could be that there are no cost differences between the MechaCar and the competition. And the alternate hypothesis could be that there are differences between the two.
To test this, a two way t-test could be performed to compare the means of the two to show if there is statistically different costs.
The data needed to run this test would be price ratings of each car type, listed costs and actual costs. 
