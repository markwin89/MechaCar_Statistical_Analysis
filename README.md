# MechaCar_Statistical_Analysis
## Overview
### Linear Regression to Predict MPG
  - Using the dataset of 50 prototype MechaCars to design a linear model that predicts the MPG of MechaCar prototypes.   
![Deliverable 1 Output](https://user-images.githubusercontent.com/101272613/177072225-0194abcb-2d34-4ff2-8370-8feaf601fb88.PNG)
  - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    - The non-random variance coefficients are vehicle length, ground clearance and mpg due to being less than .05 of significance.  The random variance coefficients are vehicle weight, spoiler angle, and AWD.  
  - Is the slope of the linear model considered to be zero? Why or why not?
    - The P-Value is 5.35e-11 which is close to 0 but the slope is not zero. 
  - Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  
    - The R-Squared is .7149 or about 71%. The R-square value is the percentage that the model correctly predicts the mpg.  We cannot soley rely on r-square when there are other data missing from the dataset. 
    
### Summary Statistics on Suspension Coils
  - Using the suspension coil dataset to create a summary (mean, median, variance, standard deviation) table below. 
  
![total_summary Deliverable 2](https://user-images.githubusercontent.com/101272613/177072943-c82d1f42-8153-4bc8-bdc0-ce36e2836cc7.PNG)

![lot_summary Deliverable 2](https://user-images.githubusercontent.com/101272613/177072939-cc458b1a-fee4-4f06-8781-af36e6232e2e.PNG)

  - The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    - Based on the total summary table, the current manufacturing data states the variance (62) is under the 100 (PSI). 
    - The outlier is Lot3 causing a large jump of the overall variance.  The variance is 170 while the other 2 lots are under 10 digits.  
    
### T-Tests on Suspension Coils
![t test PSI mu 1500 Deliverable 3](https://user-images.githubusercontent.com/101272613/177075854-2a74ad12-d08b-4c88-b567-21f87450796d.PNG)

![t test 3 manu lot mu 1500 Deliverable 3](https://user-images.githubusercontent.com/101272613/177075859-b05061b8-78b1-4edf-9268-232f87cd5fba.PNG)
  - Lot 1 has a mean of 1500 and P-Value 1.  This means we cannot reject the null hypothesis and no difference between sample mean and population mean of 1500.  
  - Lot 2 is similar to Lot 1.  The mean is 1500.02 with the P-Value of 0.6072 which we cannot reject the null hypothesis.  
  - Lot 3 has a mean at 1496.14 and P-Value of 0.04168.  In this case, we have to reject the null hypothesis. 
    - Lot 3 needs to be under review of production since the data shows outliers in that lot. 
    
### Study Design: MechaCar vs Competition
Metrics that competitors used: MSRP, color, safety rating, MPG, engine size, and car size category. 
  - The next metrics tested: MPG, engine size, car size category, expense.
Null hypothesis or alternative hypothesis
  - The null hypothesis: MechaCar list price correlates to the car size category. 
  - The alternative hypothesis: MechaCar list price does not correlates to the car size category.
  
A scatter box plot with competition list prices on the same car size category will reflect the range.   
  

    
