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



An RScript is written to create a total summary dataframe that has the mean, median, variance, and standard deviation of the PSI for all manufacturing lots (10 pt)
An RScript is written to create a lot summary dataframe that has the mean, median, variance, and standard deviation for each manufacturing lot (10 pt)
There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually (5 pt)
Deliverable 3: T-Tests on Suspension Coils (20 points)
Deliverable 3 Instructions

Using your knowledge of R, perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.
In your README, create a subheading ## T-Tests on Suspension Coils, then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

Deliverable 3 Requirements
You will earn a perfect score for Deliverable 3 by completing all requirements below:

An RScript is written for t-test that compares all manufacturing lots against mean PSI of the population (5 pt)
An RScript is written for three t-tests that compare each manufacturing lot against mean PSI of the population (10 pt)
There is a summary of the t-test results across all manufacturing lots and for each lot (5 pt)
Deliverable 4: Design a Study Comparing the MechaCar to the Competition (20 points)
Deliverable 4 Instructions

Using your knowledge of R, design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

Follow the instructions below to complete Deliverable 4.

In your README, create a subheading ## Study Design: MechaCar vs Competition.
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?

You will earn a perfect score for Deliverable 4 by completing all requirements below:

The statistical study design has the following:
A metric to be tested is mentioned (5 pt)
A null hypothesis or an alternative hypothesis is described (5 pt)
A statistical test is described to test the hypothesis (5 pt)
The data for the statistical test is described (5 pt)
Submission
Once you’re ready to submit, make sure to check your work against the rubric to ensure you are meeting the requirements for this Challenge one final time. It’s easy to overlook items when you’re in the zone!

As a reminder, the deliverables for this Challenge are as follows:

Deliverable 1: Linear Regression to Predict MPG
Deliverable 2: Summary Statistics on Suspension Coils
Deliverable 3: T-Test on Suspension Coils
Deliverable 4: Design a Study Comparing the MechaCar to the Competition
Upload the following to your MechaCar_Statistical_Analysis GitHub repository:

The MechaCarChallenge.RScript file.
An updated README.md that has the written summaries for Deliverables 1, 2, and 3 and your design for a statistical study comparing vehicle performance of the MechaCars against other manufacturers’ vehicles.
To submit your challenge assignment in Canvas, click Submit, then provide the URL of your MechaCar_Statistical_Analysis GitHub repository for grading. Comments are disabled for graded submissions in BootCampSpot. If you have questions about your feedback, please notify your instructional staff or the Student Success Manager. If you would like to resubmit your work for an improved grade, you can use the Re-Submit Assignment button to upload new links. You may resubmit up to 3 times for a total of 4 submissions.
