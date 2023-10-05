# Predict the correct flight price based on the variables to make the prediction. 
The model's performance will be evaluated based on its ability to minimize the Root Mean Square Error (RMSE) between the model's predicted values and the actual flight prices.
The dataset is in CSV format, which consists of various features related to flight prices, such as departure city, destination city, date and time of flight, flight duration, airline, etc. 
My mission is to extract valuable insights from this data and create a model that can predict flight prices as accurately as possible.

Data Dictionary
Here are the column values and their descriptions:
The columns are as follows: 

Flight_ID: A unique identifier for each flight.
Airline: The airline operating the flight.
Departure_City: The city from which the flight departs.
Arrival_City: The city where the flight arrives.
Distance: The distance between the departure and arrival cities (in kilometers).
Departure_Time: The time of day when the flight departs (in 24-hour format).
Arrival_Time: The time of day when the flight arrives (in 24-hour format).
Duration: The duration of the flight (in hours).
Aircraft_Type: The type of aircraft used for the flight.
Number_of_Stops: The number of stops during the journey.
Day_of_Week: The day of the week when the flight takes place.
Month_of_Travel: The month when the flight takes place.
Holiday_Season: Indication of whether the flight occurs during a holiday or a specific season.
Demand: A metric representing the demand for flights on that specific route.
Weather_Conditions: Weather conditions during the flight.
Passenger_Count: The number of passengers on the flight.
Promotion_Type: The type of promotion offered for the flight. 
Fuel_Price: The cost of fuel (per liter), which can significantly influence ticket prices.
Flight_Price: The price of the flight ticket.
