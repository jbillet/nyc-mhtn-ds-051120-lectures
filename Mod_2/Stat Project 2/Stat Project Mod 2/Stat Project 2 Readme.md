## Used Car Analysis Project
Flatiron Module 2 Statistics Project Joey Billet

### Project Overview
Analyzing and predicitng the prices of used cars based on a vehicles features.

After finding a dataset on Kaggle: 
- Cleaned and analyzed data using the Pandas Library
- Visualized the data using the MatPlotlib and Seaborn Libraries

The area’s in which our team looked to address are:
- How much of a factor do car features play in regards to pricing?
- Does the amount of mileage on a used car effect the price??
- Does the "time-remaining" on a used car bid directly effect price?
- Are the age and price of a used car independent of each other?

### Hypothesis Test
#### Using an Anova Test, the Hypothesis was as follows:

- H0: There is no significant difference in used car prices and mileage

- Ha: There is a significant difference in used car prices and mileage

#### Conclusion of Anova Hypothesis Test
- Result is significant with very low p-value. We can reject the null which the means are equal for these groups.



![dependent_mileage_price.png](attachment:dependent_mileage_price.png)

#### Using a Chi-Squared Test, the hypothesis test was as follows:

- Condition and Price are independent with used cars 

- Condition and Price are not independent with used cars

- Reject null hypotheis that two features (condition and price) are independent

![condition_price.png](attachment:condition_price.png)

#### Using a Chi-Squared Test, the hypothesis test was as follows:


- H0: Year and Price are independent with used cars 

- Ha: Year and Price are not independent with used cars

Reject null hypotheis that two features (year and price) are independent

![dependent_mileage_price.png](attachment:dependent_mileage_price.png)

- Will a used car be more expensive the older it is? 


![year_2.png](attachment:year_2.png)

- Due to the positive correlation, the newer a car is, the more expensive it is.

### Model Testing

- I tested a Linear Regression Model, Lasso Model, Second Degree Polynomial Model, and Third Degree Polynomial Model.

- After running the models, the Lasso Model was most accurate on average with a Root Mean Square Error of $5,631.00

        Training RMSE: 5033.116070372421
        Testing RMSE: 5631.757613282632

### Conclusion
- The age of a car, mileage, and how much time is left on the bidding all play a crucial factor in a car's price.


```python

```
