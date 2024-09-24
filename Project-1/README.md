# New York City Taxi Fare Prediction

## A Data Analysis and Regression Model for TLC Taxi Fares

## Project Background
Congrats on your new job as a data analyst at a data consulting firm called Automatidata. Automatidata works with clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs.

### Scenario:
Automatidata is consulting for the New York City Taxi and Limousine Commission (TLC), which is responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. TLC has partnered with Automatidata to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered.

**Dataset Overview**:
- Data comes from over 200,000 taxi and limousine licensees.
- Covers approximately 1 million combined trips per day.

**Note**:
- The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred.
- The data shared in this project has been altered for pedagogical purposes and may not be indicative of actual NYC taxi cab rider behavior.

## Data Dictionary

| Column Name            | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| ID                     | Trip identification number                                                  |
| VendorID               | A code indicating the TPEP provider that provided the record:                |
|                        | 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.                      |
| tpep_pickup_datetime    | The date and time when the meter was engaged.                               |
| tpep_dropoff_datetime   | The date and time when the meter was disengaged.                            |
| Passenger_count         | The number of passengers in the vehicle. This is a driver-entered value.    |
| Trip_distance           | The elapsed trip distance in miles reported by the taximeter.               |
| PULocationID            | TLC Taxi Zone in which the taximeter was engaged.                           |
| DOLocationID            | TLC Taxi Zone in which the taximeter was disengaged.                        |
| RateCodeID              | The final rate code in effect at the end of the trip:                       |
|                        | 1= Standard rate; 2=JFK; 3=Newark; 4=Nassau or Westchester; 5=Negotiated fare; 6=Group ride |
| Store_and_fwd_flag      | Indicates if the trip record was held in vehicle memory before being sent to the vendor. `Y` = store and forward; `N` = not store and forward. |
| Payment_type            | A code signifying how the passenger paid:                                   |
|                        | 1= Credit card; 2= Cash; 3= No charge; 4= Dispute; 5= Unknown; 6= Voided trip |
| Fare_amount             | The time-and-distance fare calculated by the meter.                         |
| Extra                   | Miscellaneous extras and surcharges (e.g., $0.50 rush hour surcharge).      |
| MTA_tax                 | $0.50 MTA tax based on the metered rate in use.                             |
| Improvement_surcharge   | $0.30 surcharge assessed trips at the flag drop (began in 2015).            |
| Tip_amount              | Tip amount (credit card tips are included, cash tips are not).              |
| Tolls_amount            | Total amount of all tolls paid in the trip.                                 |
| Total_amount            | The total amount charged to passengers, excluding cash tips.                |

## Next Steps
Clean the dataset to handle any missing or inconsistent data points Using python.

