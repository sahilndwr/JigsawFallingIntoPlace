The Airline Reservation System is a Java-based application designed to manage flight bookings, reservations, and administrative tasks. The system provides a user-friendly interface for customers to view available flights, make reservations, and for administrators to manage flight details.

Packages and Classes:

com.jedi.models:

Flight: Represents flight details such as flight number, destination, departure time, and available seats.
Admin: Represents the admin user with credentials for managing the system.
Reservation: Handles the reservation details, including the customer information and the selected flight.
com.jedi.services:

FlightService: Manages the operations related to flights, such as adding new flights, updating flight details, and retrieving available flights.
AdminService: Manages admin-related functions, including login verification and system management tasks.
ReservationService: Handles the reservation process, including booking a flight, canceling a reservation, and viewing booking history.
com.jedi.ui:

MainUI: The main user interface of the application, allowing users to interact with the system. It provides options for customers to view flights, make reservations, and for admins to log in and manage flights.
Key Features:

User Interaction: The system greets users with options to view flights, make reservations, and log in as an admin.
Flight Management: Admins can add, update, and manage flight details.
Reservation Handling: Users can search for available flights, book reservations, and cancel bookings.
Admin Access: Admins have access to manage the system, ensuring secure and efficient operations.
Technologies Used:

Programming Language: Java
Data Storage: Could be implemented using simple data structures like lists or expanded with database integration for more robust storage.
User Interface: Console-based UI using Java standard I/O.
