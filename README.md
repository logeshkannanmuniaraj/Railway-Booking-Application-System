# Railway-Booking-Application-System:

* The Railway Booking Management System is a Spring Boot-based application designed to manage railway ticket booking and services efficiently using API. 

* It provides functionalities to handle ticket-related operations and exception handling.

Features:
* Railway Booking Management:

Book railway tickets.

Retrieve ticket details by ID.

Handle duplicate bookings and validation errors.

* Exception Handling:

TicketAlreadyExistsException – Thrown when trying to book an already existing ticket.

TicketNotFoundException – Thrown when searching for a ticket that does not exist.

TicketBodyInvalidException – Thrown when ticket details provided are incorrect or incomplete.

Technologies Used:
* Java (Spring Boot framework)
* Maven (Dependency management)
* Spring MVC (Controller and service layers)
* Exception Handling (Custom exceptions).

Tools Used:
* Postman (For BackEnd)

API Endpoints:
1. Post Mapping   - Book a new Ticket
2. Put Mapping    - Update a Ticket By ID
3. Get Mapping    - Retrieve a Ticket By ID
4. Delete Mapping - Delete a Ticket By ID
