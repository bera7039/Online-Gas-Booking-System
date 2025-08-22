**Online Gas Booking System (Python)**
This is a simple menu-driven Online Gas Booking System built in Python without using any external libraries.
It demonstrates how customers can register, login, book gas cylinders, cancel bookings, and view their booking history.
All data is stored in a JSON file so that bookings and customers persist even after the program is closed.

**Features**

✅ Customer Registration & Login

✅ Book Gas Cylinder(s) (choose payment method: Online/Cash)

✅ Cancel Bookings (only if not delivered)

✅ View Booking History with status (Booked / Cancelled)

✅ Persistent Storage using gas_data.json

#**Tech Used**

Python Standard Library only

json → store data in JSON format

os → check if file exists

datetime → record booking date & time

No need to install any extra packages. Works in Jupyter Notebook or Python terminal.

**Project Structure**
.
├── gas_booking_system.py    # Main program file
├── gas_data.json            # Data file (auto-created)
└── README.md                # Documentation

**How to Run**

Clone the repository:

git clone https://github.com/your-username/online-gas-booking.git
cd online-gas-booking


Run the Python file:

python gas_booking_system.py


Follow the menu options on screen.

**Sample Flow**

Start Menu (before login):

--- Online Gas Booking System ---
1. Register
2. Login
3. Exit


Logged-in Customer Menu:

1. Book Gas
2. Cancel Booking
3. View My Bookings
4. Logout


Example Output:

Enter your name: Priya
Enter phone number: 9876543210
Enter address: Kolkata
Set a password: *****
Registration successful!

Welcome, Priya!
Booking successful! Your Booking ID: 1

 Learning Outcomes

This project helps you learn:

How to design menu-driven applications in Python

How to use JSON files for data persistence

How to implement basic CRUD operations (Create, Read, Update, Delete)

How to build a real-world simulation of a booking system

 

