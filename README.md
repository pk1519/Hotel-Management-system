# Hotel Management System

A simple console-based Hotel Management System implemented in C++. This system allows hotel management to perform tasks such as managing rooms, checking in guests, searching for available rooms, and generating a guest summary report.

## Features

- **Room Management:** Add new rooms, search for specific room details, and view available rooms.
- **Check-In:** Register a new customer and check them into a specified room.
- **Check-Out:** Calculate and display the bill for the guest based on the number of days stayed.
- **Search Customer:** Search for a customer's booking details using their name.
- **Guest Summary Report:** Generate a report of all guests currently checked into the hotel.

## System Requirements

- C++ compiler (e.g., GCC, Clang, or MSVC)
- Compatible with Windows, Linux, and macOS


# -Project Structure
The program consists of the following classes:

Customer: Represents customer details such as name, address, phone, booking ID, and stay dates.
Room: Represents room details, including room type, size, daily rent, and status (reserved or available).
HotelMgnt (Hotel Management): Provides hotel management functionalities such as checking in, checking out, searching for rooms, and generating reports.
# Usage
After running the program, you will be presented with a menu offering the following options:

Manage Rooms: Add new rooms or search for specific room details.
Check-In Room: Register a new customer for a room.
Available Rooms: Display all available rooms.
Search Customer: Search for a customer by name.
Check-Out Room: Process the checkout and calculate the bill for a specified room.
Guest Summary Report: View a summary report of guests currently staying in the hotel.
Exit: Exit the program.



#  Limitations
The program uses a fixed-size array for storing room details, which may limit scalability.
No data persistence. All data is lost once the program terminates.
Basic error handling and input validation.



# Future Improvements
Implement a file-based or database-based data storage solution to persist data.
Add support for more room types and features.
Implement a more user-friendly graphical interface.

for help contact me -- priyanshu00909@gmail.com
