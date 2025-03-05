# Google_colab_basics
Leaning to use google Colab to analyze data
This exercise aims to find a model to predict the per capita state and local public expenditures for different states.  This data is from 1960.  The variables are as follows.
 
● EX: Per capita state and local public expenditures ($)

● ECAB: Economic ability index, in which income, retail sales, and output val(manufactures, mineral, and agricultural) per capita are equally weighted.
● MET: Percentage of population living in standard metropolitan areas

● GROW: Percent change in population, 1950-1960

● YOUNG: Percent of population aged 5-19 years

● OLD: Percent of population over 65 years of age

● WEST: Western state (1) or not (0)

Conduct your analysis following the steps below, and you are expected to write an analysis report containing all the results.
 
 1. Plot the expenditures (EX) versus each independent variable and comment on the plots.
 Describe the relationship between the expenses and each of the independent variables.
 
 2. An appropriate regression model is fitted based on the plots in part 1. Perform the
 diagnostic checks for the model you fit.  If applicable, make adjustments to your model
 by transforming the variables and/or dropping the variables that are not needed.  If you fit
 a new model, perform the diagnostic checks for the latest model.
 
 3. For the model you fit in part 2, compute and plot the leverage values and Cook’s
 distance.
 
 4. Recall that if the fitted model has p + 1 beta parameters, then the average leverage is (p + 1)/n, and cases in which the leverage exceeds twice its average are considered high-leverage cases. Are there any high-leverage cases in this example? Also, recall
 cases where Cook’s distance is greater than 1 are of great concern and where Cook’s
 distance between .5 and 1 should be looked into.  Do the values of Cook’s distance
 suggest that any cases should be flagged for study?
 
 5. Identify the case that has the high leverage and high Cook’s distance. Refit the model by
 removing the case with the high Cook’s distance. Compare the parameter estimates of
 the model that includes the case with the large Cook’s distance and without the case that
 includes the large Cook’s distance.
