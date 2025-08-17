# Airline-flight-reservation-system
Online booking of tickets in different flights for different destinations all over the world, cancellation of tickets, display of cancellation amount, refund of cancellation amount, showing  availability, flights timings, seats availability, selection, layout of the seat arrangement, food availability, change of dates and amount charged.

🌟 Features

🎟️ Book Tickets: Users can reserve seats by entering their personal details and selecting a seat.

❌ Cancel Tickets: Reservations can be canceled, and the seat status is updated accordingly.

🔄 Change Reservation: Users can modify their booking by selecting a new seat.

🧑‍✈️ Passenger Details: Displays the details of a booked passenger based on their reservation number.

📋 Get Booking Details: Shows all active reservations.

💺 Seat Allocation: Ensures that no seat is double-booked by checking seat availability.

🍽️ Food Preferences: Allows passengers to choose meal preferences (Veg, Non-Veg, No Food).

🖥️ User-Friendly Interface: Provides a clear menu-driven console interface for easy navigation.

⚙️ Installation and Usage

📌 Prerequisites

A C++ compiler (e.g., g++, MinGW, MSVC)

A terminal or command prompt

🏗️ Compilation

Navigate to the src directory and compile the program using the following command:

 cd "Flight Reservation System/src"
 g++ main.cpp -o airline_reservation

🚀 Running the Program

To run the compiled program:

 ./airline_reservation

📂 Code Structure

🛫 Flight class: Contains methods for booking, canceling, modifying reservations, and displaying passenger details.

🔄 main() function: Calls the welcome() function to display the main menu.

🏠 welcome() function: Provides an interactive menu for users to select actions.

🔢 allocate_seat_number(): Ensures that selected seats are available before confirming reservations.

🎟️ book_ticket(): Collects passenger details and assigns a seat.

❌ cancel_ticket(): Handles ticket cancellation and updates seat availability.

🔄 change_reservation(): Allows users to change their seat.

👤 passenger_details(): Retrieves details of a specific passenger.

📋 get_booking_details(): Displays all active bookings.

