Analysis of NYC taxi trip data

This project focuses on analyzing New York City yellow taxi pickups.

Data source: [NYC OpenData](https://data.cityofnewyork.us/Transportation/2016-Yellow-Taxi-Trip-Data/k67s-dv2t)

Procedures:
1. Do some statistal analysis: total pickups by date, average fare by date, average tip by date, etc.
2. Divide the NYC yellow taxi data into neighborhoods according to pickup geographic data. Neighborhood geojson data come from [NYC OpenData](https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas/cpf4-rkhq).
3. Find the neighborhood and borough of each pickup and dropoff location in the full dataset.
4. Calculate the neighborhood with the highest pickups, show the top 5 pickup neighborhoods at each hour and on each day, and identify the most frequent morning and late night pickups.
5. Predict yellow taxi pickup frequencies by neighborhood using Random Forests.
