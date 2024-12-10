# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
    The R Squared coefficient for my model is 0.86. This means that the model is really good in relation to the data. The closer to 1, the better that a perfect positive correlation exists. It's closer to 1, and is way more accurate than the other models we've worked on so far.

2. Is your model accurate? Why or why not?
    I'd say its decently accurate, but it's not fully. If we truly want the model to be fully accurate, we need to achieve to as close of a proximity to 1. Currently the models stands at 85 or 86, it needs atleast 15 or 14 more percent points to be fully 1. The closer we are, the better. It's an okay estimation, way better than 50s, but it still needs to be worked on. 

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
    For my model, it predicted for a 10 year old car with 89000 gas miles, being a cost of around 8,912.75 dollars. A car that's 20 years old with 15,000 miles is a cost of 1,384.03 dollars.

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
    I'm assuming that no one wants to buy the car at all. If the age is really high and so is the mileage, clearly an older person doesn't wanna buy a car that has too much miles. It's a worn out car, and it'd be better to invest in a car that's more likely brand new, or minimally used. It's in the negatives, because clearly the data suggests that no one wants the old car. 