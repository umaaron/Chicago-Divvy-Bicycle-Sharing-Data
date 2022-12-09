# Tableau Visualization and Analysis of Chicago-Divvy-Bicycle-Sharing-Data Tableau Visualization and Analysis

## Divvy Data:
https://ride.divvybikes.com/system-data

## Divvy Data include two tables
Taken between Jan -June,2019

Stations table:
* ID
* Lattitude
* Longitude
* Station Name

Trips table:
* Bike ID: Id for each bike
* Birthyear: birth year of rider
* Gender: gender of rider
* End Time: day and time trip ended
* From Station  Name: station name of start
* End Station Name: station name of end
* From Station ID: station ID of trip start
* To Station ID: station ID of trip end
* Usertype: customer or subscriber
* Tripduration: time of trip in seconds
* Trips(Count): count of number of tips


## Note
### User type:  
Customers: don't have informations,which is null values for gender and birthyear. 
If Subscribers cancel their subscription and become customers, in that case, the gender and birthdayyear will be kept.
