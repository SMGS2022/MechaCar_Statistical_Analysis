# MechaCar_Statistical_Analysis

## Objective

Create a multiple linear regression that analysis and identifies which variables amongst the datasets predict the Miles Per Gallon (mpg) of an automotive data set.

## Linear Regression Predicting MPG

### Model 1: 

##### summary(lm(mpg ~ vehicle_length + vehicle_weight + spoiler_angle + ground_clearance + AWD, data=mecha_mpg))

![D1c.png](MechaCar/Images/D1c.png)

![D1d.png](MechaCar/Images/D1d.png)

All of the variables checked against mpg, ground clearance, and vehicle length, are all statistically significant (2.6x10-12 and 5.2x10-8). The correlation amongst these variables is (71.5%). 

### Model 2:

##### summary(lm(mpg ~ vehicle_length + ground_clearance, data=mecha_mpg))

![D1a.png](MechaCar/Images/D1a.png)

![D1b.png](MechaCar/Images/D1b.png)

In running the linear regression on just the vehicle length and the ground clearance, vehicle length becomes less statistically significant (7.7x10-12 ) and ground clearance becomes more statistically significant (3.3x10-8). The correlation amongst these variables is (67.4%).

## Zero / Non-Zero Slopes

![D1c1.png](MechaCar/Images/D1c1.png)

Each variable used results in the linear model having ALL Non-Zero slopes

## Suspension Coils Statistics

![D2.png](MechaCar/Images/D2.png)
