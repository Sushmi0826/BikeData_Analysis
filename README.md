# BikeData_Analysis
Bike Sharing Data Pipeline for Usage Pattern Analysis
-----------------------------------------------------
● A bike-sharing company collects vast amounts of data about its bike rental services.
● By analyzing this data can provide valuable insights that help the company optimize its operations, improve user experiences, and make informed business decisions.
● They need to build a data pipeline that collects, processes, and analyzes data from various sources to generate meaningful insights for decision-making.
● Here My task is to design and implement the data pipeline to support this analysis

DATASET:
--------
● The dataset for this project will consist of the Chicago Divvy Bicycle Sharing Data, 
which includes the following information:
● trip_id: Unique identifier for each trip.
● year, month, week, day, hour, usertype, gender, starttime, stoptime: Various details 
about the trip and the user.
● tripduration: Duration of the trip in minutes.
● temperature, events, from_station_id, from_station_name, latitude_start, longitude_start, dpcapacity_start, to_station_id, to_station_name, latitude_end, 
longitude_end, dpcapacity_end: Various details about the start and end stations

Overall architecture flow:
-------------------------

CSV ----> MYSQL ----> HDFS ----> HIVE ----> SPARK ----> HIVE ----> POWER BI

Conclusion:
-----------
● We can see that most of the bikes are taken from 8 to 9 AM 
● Most trips have an average duration of 12 minutes and this has not changed through the years
● The Clinton St & Washington Blvd(Id : 91) is very popular for pick-ups and drop-offs.
● It has revealed a clear and positive correlation between trip distance and trip duration. This means that as the distance of a trip increases, so does the time it takes to complete it.
● The male count is greater than the female count throughout the year for bike rides.


