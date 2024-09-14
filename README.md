Problem Statement:

Air ticket prices fluctuate significantly due to factors like demand, time, and airline reputation. Predicting ticket prices accurately can help airlines optimize pricing strategies and assist passengers in planning affordable trips. This project addresses the challenge of predicting ticket prices based on historical data.

Data Description

The dataset comprises 10,684 rows and 11 columns with the following key attributes:

Airline: The airline operating the flight.

Date_of_Journey: The flight’s departure date.

Source: The departure city.

Destination: The arrival city.

Route: The flight path.

Dep_Time: Departure time.

Arrival_Time: Arrival time.

Duration: Duration of the flight.

Total_Stops: The number of stops in the flight.

Additional_Info: Any additional information about the flight.

Price: The ticket price.

Exploratory Data Analysis (EDA)

Price vs Destination: Delhi shows the highest price variance with significant outliers, while Hyderabad has more stable pricing.

Price vs Source: Flights originating from Delhi and Kolkata tend to have higher prices.

Price vs Airlines: Premium carriers like Jet Airways generally charge higher fares compared to budget airlines.




The Random Forest Regressor performed the best with a training R² of 0.92 and a testing R² of 0.83. Future work could involve exploring more advanced models and incorporating additional features like seasonality, holidays, and weather conditions.

Future Work:
Include real-time ticket pricing data to enhance model predictions.
Explore deep learning models to improve accuracy further.
Develop a web-based dashboard for users to input flight details and receive predicted prices.



Technologies Used
Python: For data analysis and model building.
Pandas, NumPy: For data manipulation and preparation.
Matplotlib, Seaborn: For data visualization.
Scikit-learn: For machine learning models.
Jupyter Notebook: For running and documenting the project.
