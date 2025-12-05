# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: SquareFeet 

**Explanation:**
Feature importance is found by getting the absolute values of the model's coefficients. Larger coefficients show a stronger influence on the predicted price, and bedrooms has the largest at 6648.97. SquareFeet has the lowest at 121.11 meaning it will not have a strong influence on predicted prices.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:** Bedrooms
Each additional bedroom increases the house price by $6,648.97.

**Feature 2:** Age
Each additional year of age reduces the predicted price by $950.35.


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R² was 0.9936 which says the model can explain 99.36% of all the variation in housing prices. The model fits well and the RMSE being so low shows that the error percentage is low. There could be small improvements, but most variation is captured by these 4 variables.


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Neighboorhood/Location Ratings

**Why it would help:**
Location often has a big impact on pricing, depending on if it's a good neighboorhood or poor location and it can include nearby schools, ammenities, and access to things. It would allow non-physical aspects of the house to be used in pricing.

**Feature 2:**
Lot Size

**Why it would help:**
Homes with more land would go for more compared to a smaller lot, even if they have the same sqft. Depending on the location above, if city or rural the prices of land would also change depending on the area. It would allow the model to include lots of space that could not be calculated before.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
No, I would not trust it as it goes beyond all data available to train the model. The max bedrooms is 5, max bathrooms is 3, max squarefootage is 2500, and the lowest age is 5. So it goes out of 3/4 of the areas so the data cannot be trusted.

