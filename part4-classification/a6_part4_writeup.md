# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that? I got a number of 79% This is because it wasn't scaled up. It is still an okay number, could be better.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
    I got for the standard scaler a 82%. I think that maybe there might be another way to make it a bit better, but it mostly seems accurate for this case. Most of the predictions are correct, and it does seem like an okay accuracy for this case.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
    It got most of its predictions and actual results correct. The model did good. The pattern seems random in my opinion, I might be entirely wrong, but I don't really seem to see a connection. Maybe one connection, that being the constant number of 0.98019606 appearing in the wrong results in the numbers of three present. Some correct ones also use that number, so that might be just grasping at a straw. 
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
    No they would not.
    

