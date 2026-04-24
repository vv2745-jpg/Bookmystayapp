 feature/UC9-Error-Handling-Validation
This project presents the design and implementation of a Hotel Booking Management System to illustrate the practical application of Core Java and fundamental data structures in real-world scenarios
Use Case 9: Error Handling & Validation
Goal: Strengthen system reliability by introducing structured validation and error handling, ensuring that invalid inputs and inconsistent states are detected and handled early.
Actor:
Guest – provides booking input that must be validated.
Invalid Booking Validator – validates input and system state before processing requests.
Flow:
Guest provides booking input.
System validates input values and system constraints.
If validation fails, an error is raised immediately.
A meaningful failure message is displayed.
The system prevents invalid state changes and continues running safely.

# BookMyStayApp
This project presents the design and implementation of a Hotel Booking Management System to illustrate the practical application of Core Java and fundamental data structures in real-world scenarios
Use Case 5: Booking Request (First-Come-First-Served)
Goal: Handle multiple booking requests fairly by introducing a request intake mechanism that preserves arrival order, reflecting real-world booking behavior during peak demand.
Actor:
Reservation – represents a guest’s intent to book a room.
Booking Request Queue – manages and orders incoming booking requests.
Flow:
Guest submits a booking request.
The request is added to the booking queue.
Requests are stored in arrival order.
Queued requests wait for processing by the allocation system.
No inventory mutation occurs at this stage.
 dev
