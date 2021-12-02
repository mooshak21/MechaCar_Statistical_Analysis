## Linear Regression to Predict MPG

![](https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D1LinReg.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
>Both vehicle_length and ground_clearance; This is due to the very low p values which correlate to a high level of significance. 

- Is the slope of the linear model considered to be zero? Why or why not?
>In this case we are considering "the slope is zero" as our null hypothesis and "the slope is not zero" as our alternative hypothesis. Based on our p value being lower than the standard alpha value of 0.05, we will reject the null hypothesis meaning the the slope is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
>Using the R-Squared value of 0.7149, we can say that the linear model does in fact predict the MPG of the cars effectively. This means that approximately 71 out of 100 times the model would predict the MPG correctly. 

## Summary Statistics on Suspension Coils
Total Summary
https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D2TotalSummary.png

Lot Summary
https://github.com/mooshak21/MechaCar_Statistical_Analysis/blob/main/Resources/D2LotSummary.png

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
> The variance when looking at the total summary is 62.29 which meets the design specifications. When looking at the individual lot summaries, we get lot 1: 0.98, lot 2: 7.47, and lot 3: 170.29. Clearly, lot 1 and 2 meet the design specifications but the same cannot be said about lot 3 since it is above 100. 

# Deliverable 3

In your README, create a subheading ## T-Tests on Suspension Coils, then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

# Deliverable 4



In your README, create a subheading ## Study Design: MechaCar vs Competition.
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?