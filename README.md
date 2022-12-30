# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Linear Regression Table](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/a576f81fb65226725a9ebdb538a0e1ab4dd8cc70/Table%201.png)
The variables that provided a non-random amount of values to the mpg values in the dataset include the vehicle weight and ground clearance values and also the intercept value.
The slope of the linear model is not considered to be zero due to the fact that the p value is significantly smaller than 0.05 and also with the fact that the r-squared value is 0.71 it means that 71% of our predictions using this linear model would be correct so yes this linear model predicts MechaCar prototypes effectively

## Summary Statistics on Suspension Coils
![Total Summary](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/Total%20Summary%20DF.png)
![Lot Summary](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/Lot%20summary%20DF.png)
According to the results obtained in the total summary dataframe, the current manufacturing data meets the design specifications of not exceeding 100 pounds per square inch as the variance obtained was a value of 62.3. The lot summary dataframe shows that manufacturing lots 1 and 2 both meet the design specification with values of 0.98 and 7.47 respectively while Lot 3 has a variance that goes above the specified requirements at 170.29.

## T-Tests on Suspension Coils
![First t-test](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/first%20t-test.png)
In this analysis, the p-value obtained was 0.06028 which is more than the common significance level of 0.05% therefore we will fail to reject our null hypothesis with this dataset which is that the PSI across all manufacturing lots is not statistically different from the population mean of 1500 pounds per square inch

![Lot 1 T-test](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/Lot%201%20t-test.png)
For Lot 1, the p value obtained from the calculation was 1. This is a significantly higher value than 0.05% hence we do not have sufficient evidence to reject the null hypothesis, and as such we would state that the two means are statistically similar.

![Lot 2 T-test](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/Lot%202%20t-test.png)
Manufacturing Lot 2 analysis produced a p-value of 0.6072 which when compared to 0.05% is a higher value and so we fail to reject the null hypothesis and see that the means are statistically similar between Lot 2 and the population mean.

![Lot 3 T-test](https://github.com/SNwokolo/MechaCar_Statistical_Analysis/blob/6337d8a164a30c7d577444c00f50dd6ec4b22ef0/Lot%203%20t-test.png)
According to the calculations done for manufacturing lot 3, the p-value obtained was 0.04168 which when compared to a 0.05% significance level, we can see that it is a lower value. In this case, we reject the null hypothesis and can say that the mean here is not statistically similar to the population mean of 1500 pounds per square inch.