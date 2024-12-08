# Part 2 - Training and Testing Data Writeup

After completing `a6_part2.py` answer the following questions

## Questions to answer

1. What makes this model more effective than the model you created in the previous lesson? This model is more effectgive because it shows the training and testing data, and the predictions. Furthermore, training the data is helpful to seeing how accurate the model is.

2. What does the R squared coefficient tell you about the model?
The R squared coefficient is around .50 which means the model isn't that accurate.

3. Would you say that your model is accurate? What evidence supports your conclusion? Consider the meaning of the predicted and actual values in the context of the chart below from the American Heart Association’s website on understanding blood pressure.
It's not accurate at all. The differences are off by quite a margin. An example of this can be seen when my model projected that for a 44 year old, the answer would be a blood pressure of 134.09. In reality the person had one of 160. This is something huge, had we followed the 139 projection, the person would be in High Blood Pressure Stage 2, which is pretty bad. The reality of the situation was more dire, the person was 160, with a HYPERTENSIVE CRISIS, which means that they would've had to call the doctors immediately: This is a life or death consequence situation. This is a huge margin of error, and we need to be precise when dealing with this. 
