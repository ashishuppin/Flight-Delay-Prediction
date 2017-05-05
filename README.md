# Flight-Delay-Prediction
Dataset Description

The dataset for this problem was obtained from the Bureau of Transportation Statistics(Kaggle.com) which consists of all commercial flight operations in the year, 2015. But in order to limit the size of the dataset, a subset of the dataset has been obtained with a count of 5000 rather than 1 Million Records. 
The dataset consists of some of the following flight features: 
•	YEAR : Year Of Flight Departure/Arrival 
•	DEP_TIME : Flight Departure time in Hours 
•	DAY_OF_WEEK : Day of Week (1-7) 
•	ARRIVAL_DELAY : Difference in minutes between scheduled and actual arrival time.
•	Delayed: Arrival Delay Indicator, 20 Minutes or More (1=Yes) 
•	DISTANCE : Distance between origin and destination in miles. 
•	CARRIER_DELAY: Carrier Delay, in Minutes 
•	WEATHER_DELAY: Weather Delay, in Minutes 
• AIR_DELAY: National Air System Delay, in Minutes 
•	SECURITY_DELAY: Security Delay, in Minutes 
•	LATE_AIRCRAFT_DELAY: Late Aircraft Delay, in Minutes

Important Attributes chosen 
In order to build the predictive model, the following attributes have been considered: 
•	Timeslot 
•	Carrier 
•	Distance 
•	Day of Week
•	Taxi In/Out Time

# Machine Learning Algorithms Used
For the purpose of this project 2 types of models have been built and accuracy of both models have been compared. The 5 algorithms used are: 
•	Naïve Bayes Classification Algorithm 
•	Random Forest Algorithm
•	SVM Algorithm 
•	Linear Regression Algorithm
•	KNN Classification Algorithm 

Initial discovery of relationships is usually done with a training set while a test set and validation set are used for evaluating whether the discovered relationships hold. More formally, a training set is a set of data used to discover potentially predictive relationships. A test set is a set of data used to assess the strength and utility of a predictive relationship.

For the purpose of our predictive model, 80% of the data has been used as training data (to train the classifier) and 20% of the data has been considered as test data.
