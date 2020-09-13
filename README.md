# CampgroundReservation
Java application that searches a database for available campsites and creates reservations. This is a capstone project I worked on in collaborative environment during my time at Tech Elevator.

This application uses PostgreSQL and a JdbcTemplate to access a local database of reservations within multiple campgrounds in multiple National Parks.

A user can search for availability in a campground for a given duration of days. Results are sorted by occupancy capacity and various amenities available.

A user can then select a reservation from the results to book. At this point, the database is updated with the new reservation. 

