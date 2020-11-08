## Projects Review

### Background
A hotel business owner it’s having difficulty staffing the appropriate amount of personnel due to special requests in the hotel. Considering the amount of cancelations, sometimes the hotel is overstaffed or understaffed.

### Objective
My task is to predict the amount of special requests the hotel will receive based on booking/special request historical data. the hotel would like to know the special requests it is likely to receive, in order to know how many staff it will require.

Based on the data, the number of booking cancelations in a binary value (1) for no cancel and (0) for cancel. The analysis shows the type of deposit, the distribution channel, the arrival month, and the number of adults can help to predict the amount of special requests the hotel could receive. I use a logistic regression model, decision tree model and random forest model to predict the cancellation probability for each booking. In this case, a random forest model gives the best result.

### Achievement
By using the RF model and setting a certain confidence level for the prediction, the actual booking status can be predicted, and thus help the owner decide the staffing status to save the operational cost.
