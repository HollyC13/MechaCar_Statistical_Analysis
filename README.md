# MechaCar_Statistical_Analysis
Module_15

## Summary
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. A review of production data is launched in an effort to assist the production team.

### Summary - Deliverable 1
Data includes a sample of 50 observations with variables miles per gallon (mpg), vehicle_length, vehicle_weight, spoiler_angle, ground_clearance and All Wheel Drive (AWD).

![Summary Analysis](/Resources/Del1Summary.png)

##### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Our analysis of p-values for each variable shows the intercept, vehicle_length and ground_clearance provide a non-random amount of variance to the mpg values in our dataset.
These variables show a statistically significant impact on mpg.
 	
##### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because analysis shows correlation between some independent variables.

##### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Lack of significant variables is evidence of overfitting, indicating the model performs well with the current dataset but fails to generalize and predict future data correctly.  With six variables and a sample size of 50, our sample dataset is considered to be overfitted by some standards.

Using more than 5 independent variables may result in multicollinearity, where two or more of the variables are highly correlated to one another, impacting the analysis.

Considering the possibility of overfitting and multicollinearity, along with a Multiple R-squared of 0.7149 and an adjusted R-squared of 0.6825, this linear model predicts the mpg of MechaCar prototypes adequately.  Additional analysis after addressing sample size and potential multicollinearity should provide more reliable results.

### Summary Statistics on Suspension Coils - Deliverable 2
Data includes a sample of 150 observations with variables VehicleID, Manufacturing_Lot and PSI (pound-force per square inch).

This table shows the mean, median, variance and standard deviation values for the PSI variable.

![Summary Analysis](/Resources/Del2TotalSummary.png)


This table shows the mean, median, variance and standard deviation values for the PSI variable by Manufacturing_Lot.

![Summary Analysis-PSI](/Resources/Del2LotSummary.png)


#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The calculated variance shows all manufacturing lots in total, Lot1 and Lot2 meet the design specification.  The mean and median further indicate the consistency in PSI values for these groups.  Lot3 does not meet the design specification with a calculated variance of 170.29.  A minimum value of 1452 and maximum value of 1542, along with the mean and median, further illustrate how widely the values vary for this group.


### T-Tests on Suspension Coils - Deliverable 3
One-sample t-tests were performed to determine if there is a statistical difference between the means of our sample dataset and a hypothesized, potential population dataset.  A population mean of 1,500 PSI is used.


Total dataset:  Using a significance level of 0.05 percent, a p-value of 0.06 is above significance level.  There is not sufficent evidence to reject the null hypothesis and the
two means are statistically similar.

![PSI-All](/Resources/Del3PSIALL.png)



Lot 1:  Using a significance level of 0,05 percent, a p-value of 1 is above significance level.  There is not sufficent evidence to reject the null hypothesis and the two
means are statistically similar.

![PSI-Lot 1](/Resources/Del3Lot1.png)



Lot 2:  Using a significance level of 0.05 percent, a p-value of 0.61 is above significance level.  There is not sufficent evidence to reject the null hypothesis and the two
means are statistically similar.

![PSI-Lot 2](/Resources/Del3Lot2.png)



Lot 3:  Using a significance level of 0.05 percent, a p-value of 0.04 is below significance level.  The null hypothesis is rejected and the two means are not statistically
similar.

![PSI-Lot 3](/Resources/Del3Lot3.png)



