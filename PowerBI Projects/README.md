# PowerBI Projects
This folder contains PowerBI projects for the portfolio. There is .pbix files and the sources with description.

**IMPORTANT:** To use the PowerBI files you need to download the sources and change the data sources using the power query tool.

# HIGHLIGHT ANALYSIS (NYC Taxi Analysis)

## Reports
- Employee Analysis
![Employee Analysis](/NYC%20Taxi%20Analysis//images/NYC_Taxi_Employee_Analysis.png)
- Speed Analysis
![Speed Analysis](/NYC%20Taxi%20Analysis/images/NYC_Taxi_Employee_Analysis.png)
- Vendor Analysis
![Vendor Analysis](/NYC%20Taxi%20Analysis/images/NYC_Taxi_Employee_Analysis.png)
## Datasets

**Source**:
https://www.kaggle.com/microize/newyork-yellow-taxi-trip-data-2020-2019?select=yellow_tripdata_2020-05.csv

**Open Source Data**

Context
The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

**Content**

Column Description

VendorID : A code indicating the TPEP provider that provided the record.

-  1= Creative Mobile Technologies, LLC;
-  2= VeriFone Inc.

tpeppickupdatetime : The date and time when the meter was engaged.

tpepdropoffdatetime : The date and time when the meter was disengaged.

Passenger_count : The number of passengers in the vehicle.( This is a driver-entered value )

Trip_distance : The elapsed trip distance in miles reported by the taximeter.

PULocationID : TLC Taxi Zone in which the taximeter was engaged

DOLocationID :TLC Taxi Zone in which the taximeter was disengaged

RateCodeID : The final rate code in effect at the end of the trip.
- 1= Standard rate
- 2=JFK
- 3=Newark
- 4=Nassau or Westchester
- 5=Negotiated fare
- 6=Group ride

store_andfwd_flag : This flag indicates whether the trip record was held in vehicle memory before sending to the vendor, aka “store and forward,because the vehicle did not have a connection to the server.
- Y= store and forward trip
- N= not a store and forward trip

Payment_type A numeric code signifying how the passenger paid for the trip.
- 1= Credit card
- 2= Cash
- 3= No charge
- 4= Dispute
- 5= Unknown
- 6= Voided trip

Fare_amount : The time-and-distance fare calculated by the meter.

Extra : Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.

MTA_tax : $0.50 MTA tax that is automatically triggered based on the metered rate in use.

Improvement_surcharge : $0.30 improvement surcharge assessed trips at the flag drop. The

improvement surcharge began being levied in 2015.

Tip_amount : Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.

Tolls_amount : Total amount of all tolls paid in trip.

Total_amount : The total amount charged to passengers. Does not include cash tips.

------------------------------------------------------------------------
## Acknowledgements

Data is obtained from NYCTaxi & Limousine Commission website.
https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page