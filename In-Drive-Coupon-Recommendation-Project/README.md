# In-Drive-Coupon-Recommendation-Project

## Problem Statement:
This data was collected via a survey on the Ecom website Mechanical Turk. The survey describes different driving scenarios including the user’s destination, weather, passenger, coupon attributes, 
user attributes, and contextual attributes, and then asks the user whether he/she will accept the coupon or not. In this project we have to predict if the user will accept the coupon.

## Objectives:
1. Exploratory Data Analysis: Data Preprocessing and Data Visualization
2. Comparing performance of different machine learning algorithms
3. Hyperparameter Tuning
4. Building a supervised machine learning classification model

## Data Dictionary:
1. Gender: Female, Male
2. Age: 21, 46, 26, 31, 41, 50plus, 36, below21
3. Marital Status: Unmarried partner, Single, Married partner, Divorced, Widowed
4. has_Children: 1: has children, 0: No children
5. Education: Some colleges — no degree, bachelor’s degree, Associates degree, High School Graduate, Graduate degree (Master or Doctorate), Some High School
6. Occupation: Traveller’s occupation
7. Income: income of the traveler
8. Car: Description of vehicle driven by the traveller
9. Bar: how many times does the traveler go to a bar every month?
10. Coffee House: how many times does the user go to a coffeehouse every month?
11. Carry Away: how many times does the user get takeaway food every month?
12. RestaurantLessThan20: how many times does the user go to a restaurant with an average expense per person of less than $20 every month?
13. Restaurant20To50: how many times does the user go to a restaurant with an average expense per person of $50 every month
14. Destination: destination of traveler
15. Passenger: who are the passengers in the car
16. Weather: weather when the user is driving (Sunny, Rainy, Snowy)
17. Temperature: temperature in Fahrenheit when the user is driving
18. Coupon: Type of Coupon
19. Expiration: Validity of Coupon
20. toCoupon_GEQ5min: driving distance to the restaurant/cafe/bar for using the coupon is greater than 5 minutes (0,1)
21. toCoupon_GEQ15min: driving distance to the restaurant/cafe/bar for using the coupon is greater than 15 minutes (0,1)
22. toCoupon_GEQ25min: driving distance to the restaurant/cafe/bar for using the coupon is greater than 25 minutes (0,1)
23. direction_same: whether the restaurant/cafe/bar is in the same direction as the traveler’s current destination (0,1)
24. direction_opp: whether the restaurant/cafe/bar is in the opposite direction as the user’s current destination (0,1)
25. Accept(Y/N?)- Target column( whether user will accept the coupon or not?)

## Comparision of performance of different algorithms
![image](https://github.com/meghrajkonduskar/In-Drive-Coupon-Recommendation-Project/assets/65845208/8fab093b-635f-46ca-8f61-2c0b1ca5cf32)

## Final Model Evaluation Metrics
![image](https://github.com/meghrajkonduskar/In-Drive-Coupon-Recommendation-Project/assets/65845208/b289705d-cac6-4f1a-a2e1-ed496ae78fa5)

## Conclusion
1. By using Hyper Parameter Tuning XGBoost was performing better than Random Forest. So created Final Model using XGBoost Classifier.
2. With 77.4% Accuracy we can now predict if the customer will accept the coupon or not.





