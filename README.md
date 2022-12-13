# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
<img width="515" alt="linear regression" src="https://user-images.githubusercontent.com/110696825/207217014-511d9de1-df77-4c7b-b5cf-67967c34f49e.png">

- Vehicle_length, ground_clearance and intercept provided a non-random amount of variance to the mpg values in the dataset.
- The slope of the linear model is not considered to be zero. The p-value of our linear regression analysis is 5.35 x 10-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.
- This linear model predict mpg of MechaCar prototypes effectively. Because from our linear regression model, the r-squared value is 0.68, which means that roughly 68% of all MPG predictions will be correct when using this linear model. 

## Summary Statistics on Suspension Coils
<img width="350" alt="total summary" src="https://user-images.githubusercontent.com/110696825/207217220-bd13f9cb-4757-417f-91d6-f5938e96c4d8.png">
<img width="505" alt="lot summary" src="https://user-images.githubusercontent.com/110696825/207217452-e9bf4025-b1c5-45a5-8388-9501b7a7fd98.png">

The total variance is 62.29 which doesn't exceed the 100 PSI variance regarding design specifications. 
However, in three lots, lot 3 actually exceeds the design specifications of 100 PSI.

## T-Tests on Suspension Coils
<img width="615" alt="Screenshot 2022-12-12 at 10 14 39 PM" src="https://user-images.githubusercontent.com/110696825/207217698-258ae4d5-460e-46a7-a30a-ad4effcd3234.png">
<img width="585" alt="Screenshot 2022-12-12 at 10 14 56 PM" src="https://user-images.githubusercontent.com/110696825/207217718-8b167114-05f5-4628-99ec-84f45f5efaa2.png">

- The p-value of total lots is 0.06, which is higher than our assumed significance level of 0.05%. It means there is significant different between population mean and mean of the total.
- The p-value of lot 1 is 1, which is much higher than our assumed significance level of 0.05%. It means there is significant different between population mean and lot 1.
- The p-value of lot 2 is 0.6, which is much higher than our assumed significance level of 0.05%. It means there is significant different between population mean and lot 2.
- The p-value of lot 3 is 0.04, which is lower than our assumed significance level of 0.05%. It means there is no significant different between population mean and lot 3.

## Study Design: MechaCar vs Competition
We can collect data and analyze the maintenance cost difference between MechaCar and competitors.
Null Hyphothesis: There is no statistical difference between MechaCar and competitor's average maintenance. 
Alternative Hypothesis: There is a statistical difference between MechaCar and competitor's average maintenance. 
I'm gonna use t-test because it's used to test mean values.
We will need the all the maintenance services cost to calculate the mean for MechaCar and competitors.
