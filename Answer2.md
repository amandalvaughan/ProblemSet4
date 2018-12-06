I am going to create a database called SFOairtraffic.sqlite

I will create three tables: Flight Activity, Flight Classification, and Operating Airline:

FLIGHT ACTIVITY

| Passenger Count (primary key) | Operating Airline Code | Activity Type | Terminal | Boarding Area |
| --- | --- | --- | --- | --- |
| Integer | String | String | String | String |

FLIGHT CLASSIFICATION

| Passenger Count (primary key) | Operating Airline Code (foreign key) | Geo Summary | Geo Region |
| --- | --- | --- | --- |
| Integer | String | String | String |

Operating Airline

| Passenger Count (primary key) | Operating Airline Code (foreign key) | Operating Airline |
| --- | ---| full name |
| Integer | String | String |
