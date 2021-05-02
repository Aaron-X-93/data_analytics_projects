## Projects Review

### Background
A hotel business owner it’s having difficulty staffing the appropriate amount of personnel due to the uncertainty of the booking requests. Considering the amount of cancelations, sometimes the hotel is overstaffed or understaffed.

### Objective
In order to identify whether a certain booking order is likely to be canceled or not, supervised learning is used with the historical order data.  Based on the data, the number of booking cancelations in a binary value (1) for no cancel and (0) for cancel. The analysis shows the type of deposit, the distribution channel, the arrival month, and the number of adults can help to predict the amount of special requests the hotel could receive. 
After deeply looking into the data and cleaning it, I built a total 3 models to compare the prediction performance: logistic regression model, decision tree model, and random forest model. In this case, the random forest model performanced best.

### Achievement
By using the RF model and setting a certain confidence level for the prediction, the actual booking status can be predicted, and thus help the owner decide the staffing status to save the operational cost.
