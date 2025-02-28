# Customer_Coupon
Analysis for Customer Coupons based on UC Irvine's Survey

# Summary of Findings
A number of conclusions:
Generally speaking, we can draw the following conclusions:

* Proximity: Across the board, the closer coupons the more likely they will be visited. 
* Age: The older the less likely coupons will be used.
* Destination: Consumers not heading home or work are twice as likely to utilize the coupons.
* Passenger: Consumers alone far more likely to utilize the coupons. Any passenger (friend, kid, partner) ensured decline of distant coupons.
* Weather: Coupons used on a sunny day are significantly more likely, up to 5X rainy or snowy days.
* Temperature: Direct correlation with temperature. The higher the temperature the more likely across all 3 coupons.
* Time: Early in the day (~7 AM) and later in the day (~6PM) coincide with people either heading to work or home and are more likely than rest of day.
* Coupon: This is the order of popularity: Coffee House, Cheap Restaurant, Carry out and Take away, Bar, Expensive restaurant.
* Gender: No major differences between genders.
* Marital Status: Single and Married are significantly more likely to utilize the coupons. It's an interestingly normal distribution.
* Children: No children is higher than with children.
* Eduction: People with Bachelors degree or some college were major users of coupon than all other groups. 
* Occupation: Unemployed and professions like Computer/Mathematical, Student, Sales/Related, Management, Education/Library were the majority of consumers of coupons.
* Income: Interestingly, income didn't contribute much to the decision.
* Bar: The fewer the times a person visited bars the more likely they were to use coupons.
* CoffeeHouse: The fewer the times a person visited coffee houses the more likely they were to use coupons.
* Carry Away: Persons who carry away 4-8 are most likely. It drops for higher and lower number of visits.
* Cheap Restaurants: Normal distribution where people visiting 1-3 are most likely to utilize coupons.
* Expensive Restaurants: The less frequently people visit expensive restaurants the more likely they utilize the coupons.

Defining the ideal persona: A young person is generally a single, unemployed college student busy during the day with school/part-time unemployment.
They have less commitments like children and often carry away their purchases and visit less expensive restaurants and may rely on public transport, hence 
are most impacted by weather as they can not travel far from their residence. This explains the recurring proximity factor across virtually all plots.

# Ideal Candidate
age = Age less than 30
distance = toCoupon_GEQ5min
destination = Not Urgent Place
passenger = Alone
weather = Sunny
education = Bachelors degree or some college
occupation = unemployed, computer and mathematical, student, sales and related
bar = never, less1
CarryAway = 1-3, 4-8
RestaurantLessThan20 = 1-3, 4-8
Restaurant20To50 = less1

# Recommendation
Coupons should target college students as they are the most likely population to utilize them.
