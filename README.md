# MechaCar_Statistical_Analysis
Module_15

## Summary
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. A review of production data is launched in an effort to assist the production team.

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
