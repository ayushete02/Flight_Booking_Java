Username: admin
Password: admin

###
Flight Booking System
This is a Java-based Flight Booking System project. The system allows users to search for flights, view flight details, and book flights. The project also includes an admin module that allows administrators to add new flights, manage existing flights, and view booking details.

Features
User registration and login
Search for flights based on departure and arrival cities, date, and time
View available flights and their details
Book flights and view booking details
Admin module to manage flights and view booking details
Secure login using encryption
Technologies Used
Java
JavaFX for GUI
MySQL for database
Maven for build management
Getting Started
Prerequisites
Java 8 or higher
MySQL database
Maven
Installation
Clone the project from the Github repository:



git clone https://github.com/ayushete02/Flight_Booking_Java.git
Create a new MySQL database and import the flight_booking_system.sql file located in the database directory.

Modify the database.properties file located in the src/main/resources directory to point to your MySQL database.

Run the following command to build the project:


mvn clean install
Run the following command to start the application:


java -jar target/flight-booking-system-1.0.jar
Usage
Register a new user by clicking the "Register" button and filling out the registration form.

Log in to the system using your username and password.

Search for available flights by clicking the "Search Flights" button and entering the departure and arrival cities, date, and time.

View flight details by clicking on a flight from the search results.

Book a flight by clicking the "Book Flight" button and entering the passenger details.

View your booking details by clicking the "My Bookings" button.

Log out of the system by clicking the "Log Out" button.

To access the admin module, log in as an administrator using the username "admin" and password "admin".

Contributing
Contributions to this project are welcome and encouraged. If you would like to contribute, please follow the guidelines outlined in the CONTRIBUTING.md file.

License
This project is released under the MIT license. See the LICENSE.md file for more details.
