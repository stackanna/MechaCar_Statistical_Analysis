# MechaCar_Statistical_Analysis

Click [HERE](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/cb14c06d03d53a0e271a796dd259fc666dc7aeda/MechaCarChallenege.RScript.R) to view [Mecha Car Statistical Analysis](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/cb14c06d03d53a0e271a796dd259fc666dc7aeda/MechaCarChallenege.RScript.R)

# Resources Used: R Studio & Visual Studio Code

# Summary Of Analysis

We are reviewing the production data for insights that may help the manufacturing team of the newest prototype for a car company, AutosRUs'. We are assisting Jeremy & the data analytics team by performing multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes. Collecting a summary of statistics on the PSI of the suspension coils from the manufacturing lots. Running t-tests to determine if the manufacturing lots are statistically different from the mean population. 




## Linear Regression to Predict MPG
Output from the linear regression:
![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/cb14c06d03d53a0e271a796dd259fc666dc7aeda/Vehicle%20MPG%20Statistics.png)
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- Vehicle length and & Ground Clearance are most likely to provide a non-random amount of variance to the mpg values in the dataset. Overall, they are will have the most impact on the MPG of the newest prototype, Mechacar. 

Is the slope of the linear model considered to be zero? Why or why not?

- The slope of the linear model is not considered to be zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- This linear modely does predict mpg of MechaCar prototypes effectively. Our R-Square value determines the variability is at around 71%. Meaning its accuracy is above 70%.

# Summary on Suspension Coil

The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/cb14c06d03d53a0e271a796dd259fc666dc7aeda/Suspension%20Summary.png)

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/cb14c06d03d53a0e271a796dd259fc666dc7aeda/Suspension%20Manufacturing%20Lot.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.The current manufacturing data does not meet this design specification for all manufacturing lots in total because they exceeded the design specifications of 100 lbs per sq inch. 
The total summary variance of 62.3 lbs per square inch which meets the design specifications for MechaCar.

## T-Tests on Suspension Coils

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/d12ae053b679fc1c01397b6ec7c39ba8d9aa56c7/T-Test.png)

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/d12ae053b679fc1c01397b6ec7c39ba8d9aa56c7/lot1%20ttest.png)

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/d12ae053b679fc1c01397b6ec7c39ba8d9aa56c7/Lot%202%20T-Test.png)

![alt text](https://github.com/stackanna/MechaCar_Statistical_Analysis/blob/d12ae053b679fc1c01397b6ec7c39ba8d9aa56c7/lot%203%20ttest.png)


Using our knowledge of R, we performed t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. All of the t-tests we performed proved that there was no statistical difference from the population mean of 1500. The p-values are not statistically significant enough to reject the null hypothesis. 

## Study Design: MechaCar vs Competition

How will the MechaCar will perform against the competition? In your study design, analyzing critically about what metrics would be of interest to a consumer: such as, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating. 

What metric or metrics are you going to test?

- We would test metrics like the most common issues with vehicles & the costs to repair them.

What is the null hypothesis or alternative hypothesis?

- There is a statistical difference between repairs made & cost variances of the MechCar prototype to most popular vehicles currently on the road. 

What statistical test would you use to test the hypothesis? And why?

- It would make most sense to run a Multiple Linear Regression & Pearsons coefficients to test our hypothesis so we can confirm if there is a statistical difference to reject or fail to reject our null hypothesises.

What data is needed to run the statistical test?

- We would need the data of the MechaCar prototpyes performance and repair costs over time compared to competitors. 

