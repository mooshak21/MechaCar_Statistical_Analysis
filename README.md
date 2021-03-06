## Linear Regression to Predict MPG

![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D1LinReg.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
>Both vehicle_length and ground_clearance; This is due to the very low p values which correlate to a high level of significance. 

- Is the slope of the linear model considered to be zero? Why or why not?
>In this case we are considering "the slope is zero" as our null hypothesis and "the slope is not zero" as our alternative hypothesis. Based on our p value being lower than the standard alpha value of 0.05, we will reject the null hypothesis meaning the the slope is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
>Using the R-Squared value of 0.7149, we can say that the linear model does in fact predict the MPG of the cars effectively. This means that approximately 71 out of 100 times the model would predict the MPG correctly. 

## Summary Statistics on Suspension Coils
### Total Summary
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D2TotalSummary.png)  

### Lot Summary
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D2LotSummary.png)

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
> The variance when looking at the total summary is 62.29 which meets the design specifications. When looking at the individual lot summaries, we get lot 1: 0.98, lot 2: 7.47, and lot 3: 170.29. Clearly, lot 1 and 2 meet the design specifications but the same cannot be said about lot 3 since it is above 100. 

## T-Tests on Suspension Coils
### All Three Lots
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D3Ttest.png)
> Null Hypothesis: mean = 1500 | Alternative Hypothesis: mean ??? 1500 -- Since the p value > alpha (0.06 > 0.05), we fail to reject the null hypothesis. This means the true value of the mean could indeed be 1500.

### Lot 1
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D3Lot1.png)
> Null Hypothesis: mean = 1500 | Alternative Hypothesis: mean ??? 1500 -- Since the p value > alpha (1 > 0.05), we fail to reject the null hypothesis. This means the true value of the mean could indeed be 1500.

### Lot 2
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D3Lot2.png)
> Null Hypothesis: mean = 1500 | Alternative Hypothesis: mean ??? 1500 -- Since the p value > alpha (0.61 > 0.05), we fail to reject the null hypothesis. This means the true value of the mean could indeed be 1500.

### Lot 3
![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D3Lot3.png)
> Null Hypothesis: mean = 1500 | Alternative Hypothesis: mean ??? 1500 -- Since the p value < alpha (0.04 < 0.05), we reject the null hypothesis affirming the alternative hypothesis. This means the true value of the mean is not 1500.

## Study Design: MechaCar vs Competition
Consumers mostly want a car that has good gas mileage so we will focus on that for this study in relation to the user's maintenance costs. 

- What metric or metrics are you going to test?
>We would use the metric of the cost for maintenance repairs.

- What is the null hypothesis or alternative hypothesis?
>Null Hypothesis: The people that use their MechaCar 5 days a week will have a lower mainenance cost than those who drive competitors cars.

- What statistical test would you use to test the hypothesis? And why?
>We would use a 2 sample t-test to relate the costs between the MechaCar group and the non MechaCar group. Our main goal is to see if the cost for each are independent. 

- What data is needed to run the statistical test?
>The make and model of the car, days the car is used per week, and the cost of maintenance.

