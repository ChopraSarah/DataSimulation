# DataSimulation

This repository has three different data simulations.

Initially there are four columns - Y, X1, X2, X3

Y is target variable
X1 independent variable. X1 is continuous.
X2 and X3 are categorical independent variables. X2 and X3 have five levels each.

Simulations:

In a linear model for above dataset we will have the final equation as:
   Y = b0 + b1*Y + b2*X22 + b3*X23 + b4*X24 + b5*X25 + b6*X32 + b7*X33 + b8*X34 + b9X35 + error

1) The first simulation, varies b9 from 1 - 5, taking five different values.
2) The second simulation (ss) varies sample size taking values 10,25,50,100,500
3) The third simulation (sg) varies variance of error taking values 0.1,0.3,0.7,1,10
