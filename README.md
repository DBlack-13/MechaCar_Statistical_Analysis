# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Linier_Regression](https://user-images.githubusercontent.com/106560752/192115553-154af02a-3b77-49f8-864c-26f7a6fe693d.png)

In this data we can see that Vehicle Length and Ground_Clearance provide a non-random amount of variance since they do not equal to 0.5, they are much smaller.

The slope of this linear model is not zero due to the fact that the data presents everything but zero numbers. In order to have a zero slope, we have to have resulted in 0s in the data given.

Since out Multiple R-Squared falls between 0-1, then we can conclude that this linear model predicts the mpg of MechaCar prototypes affectively.

## Summary Statistics on Suspension Coils
![Total_Summary](https://user-images.githubusercontent.com/106560752/192115942-046430f2-6eed-480f-b84a-8fad71e8a4f9.png)
![Lot_Summary](https://user-images.githubusercontent.com/106560752/192115947-1d5af05b-e14b-4e01-81f0-5db98d267b83.png)

Based on the data presented in Total Summary, we can see that current manufacturing data does meet the design specification of 100 psi or less as the variance is at 62.29. However, we can take a look at Lots individually we can see that there are complications with the accuracy of the data. In Lot 3, the PSI exceeds the 100 psi requirement by being at 170 psi. But, in LOT 1 and 2, each PSI is below 10. This explains why the Total Summary meets guidelines, but when we take a look at them individually there are major differences in the PSI data.

## T-Tests on Suspension Coils
![Deliverable_3](https://user-images.githubusercontent.com/106560752/192116173-f6c650c9-767d-4a27-a58c-90580d2a7e1c.png)

Here we can see that the Sample Mean is not equal to 1500 BUT they are all very very close. But when we take a look at their p-values, we can see that LOT 3 is far different from the other 2, sitting at 0.04.


