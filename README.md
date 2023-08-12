# uber_recommender_driver_ltv
Recommend Uber Driver’s Lifetime Value in Python

DATA MODEL EXPLANATION
driver_ids.csv
driver_id Unique identifier for a driver
driver_onboard_date Date on which driver was on-boarded

ride_ids.csv
driver_id Unique identifier for a driver
ride_id Unique identifier for a ride that was completed by the driver
ride_distance Ride distance in meters
ride_duration Ride duration in seconds
ride_prime_time Prime Time applied on the ride

ride_timestamps.csv
ride_id Unique identifier for a ride
event describes the type of event; this variable takes the following values:
requested_at - passenger requested a ride
accepted_at - driver accepted a passenger request
arrived_at - driver arrived at pickup point
picked_up_at - driver picked up the passenger
dropped_off_at - driver dropped off a passenger at destination
timestamp Time of event

After exploring and analyzing the data, please:
Recommend a Driver's Lifetime Value (i.e., the value of a driver to Uber over the entire projected lifetime of a driver).
Please answer the following questions:
What are the main factors that affect a driver's lifetime value?
What is the average projected lifetime of a driver? That is, once a driver is onboarded, how long do they typically continue driving with Uber?
Do all drivers act alike? Are there specific segments of drivers that generate more value for Uber than the average driver?
What actionable recommendations are there for the business?
Prepare and submit a write up of your findings for consumption by a cross-functional audience.

You can make the following assumptions about the Uber rate card:
Base Fare $2.00
Cost per Mile $1.15
Cost per Minute $0.22
Service Fee $1.75
Minimum Fare $5.00
Maximum Fare $400.00

