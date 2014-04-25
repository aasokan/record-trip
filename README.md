record-trip
==========================

Write a function called record_trip_event that takes as its arguments:
●	client_id
●	driver_id
●	start_time
●	lat
●	lng
●	fare
●	distance
●	rating

This function will be called in a loop with a bunch of trip information.  Build a system that stores this information as it comes in, and exposes it in a RESTful server interface that exposes the following aggregate data:
●	total number of trips
●	total number of clients who’ve taken trips
●	total number of trips in the last hour
●	total miles per client
●	avg fare for a specific city (where a city can be defined as a square)
●	median rating for a driver

Bonus points if you can make all of the above aggregate data endpoints take range arguments so you can find any information across the specified range in time.

Even more bonus points if your server scales up to serve many concurrent requests with the same query parameters with only a minimal increase in the server resource usage.


