# Scooter Rental Platform

A city operates a fleet of electric scooters that can be hired through a mobile application.

The business has provided the following requirements.

## Requirements

A scooter:

* Has a unique identifier.
* Has a battery percentage.
* Can be available or unavailable.

Customers should be able to:

* View available scooters.
* Rent an available scooter.
* End a rental.

Business rules:

* A scooter cannot be rented if it is already rented.
* A scooter with less than 20% battery cannot be rented.
* Ending a rental returns the scooter to the available pool.

## Additional Requirements

Once the core functionality is working, consider:

* Tracking rental duration.
* Calculating rental cost.
* Reserving a scooter before rental.
* Automatically removing low-battery scooters from availability.

## Acceptance Criteria

The behaviour should be proven through automated tests.

The implementation details are entirely your choice.