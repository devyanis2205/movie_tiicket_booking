# Movie Ticket Booking System

The Movie Ticket Booking System is a Python-based console application designed to manage movie seat bookings. The project allows users to view available seats, book seats, cancel bookings, search for a seat's booking status, view booked seats, and count the number of available seats.

This project demonstrates the use of Python functions, lists, conditional statements, loops, user input, and basic menu-driven programming.

---

## Project Overview

The Movie Ticket Booking System provides a simple way to manage movie seat bookings through a console-based menu.

The system contains a fixed number of seats divided into two rows: **A1–A5** and **B1–B5**. Users can perform different operations such as booking a seat, cancelling a booking, searching for a seat, and checking the number of available seats.

The project is developed using **Python only** and does not use any database or SQL.

---

## Key Objectives

### 1. Display Available Seats

Display all seats and show which seats are currently booked.

### 2. Book a Seat

Allow users to enter a seat number and book it if the seat is available.

### 3. Cancel Booking

Allow users to cancel a previously booked seat.

### 4. View Booked Seats

Display the list of all currently booked seats.

### 5. Search Booking

Allow users to search for a specific seat and check whether it is booked, available, or invalid.

### 6. Count Available Seats

Calculate and display the total number of seats that are still available.

---

## Features

* Display available and booked seats
* Book available seats
* Prevent booking of an already booked seat
* Cancel booked seats
* View all booked seats
* Search for a particular seat
* Count available seats
* Menu-driven console interface
* Continuous operation until the user selects Exit
* Input validation for seat numbers

---

## Seat Layout

The system contains 10 seats:

| Row | Seats              |
| --- | ------------------ |
| A   | A1, A2, A3, A4, A5 |
| B   | B1, B2, B3, B4, B5 |

---

## Tools & Technologies Used

**Python** – Programming Language

**Jupyter Notebook** – Development Environment

No SQL or database is used in this project.

---

## Python Concepts Used

* Lists
* Functions
* `if-elif-else` statements
* `for` loop
* `while` loop
* User input using `input()`
* List methods such as `append()` and `remove()`
* Membership operators (`in`)
* String methods such as `upper()`
* Basic program control using `break`

---

## Working of the System

1. The system starts by displaying the main menu.
2. The user selects an operation from the menu.
3. The user can view available seats.
4. The user can book an available seat by entering its seat number.
5. If the selected seat is already booked, the system displays an appropriate message.
6. The user can cancel a previously booked seat.
7. The user can search for a particular seat to check its status.
8. The system can display all currently booked seats.
9. The system calculates the number of available seats.
10. The program continues running until the user selects the **Exit** option.

---

## Menu Options

| Option | Operation               |
| ------ | ----------------------- |
| 1      | Display Available Seats |
| 2      | Book Seat               |
| 3      | Cancel Booking          |
| 4      | View Booked Seats       |
| 5      | Search Booking          |
| 6      | Count Available Seats   |
| 7      | Exit                    |

---

## Advantages

* Simple and easy-to-understand Python project.
* Demonstrates practical use of Python functions and lists.
* Provides basic seat booking functionality.
* Prevents duplicate booking of the same seat.
* Allows users to cancel bookings.
* Provides different options for managing seat information.
* Suitable for beginners learning Python programming.
* Helps understand menu-driven programming.

---

## Limitations

* The project is console-based and does not have a graphical user interface.
* The number of seats is fixed to 10.
* No customer information is stored.
* No movie details such as movie name, show time, or theatre are stored.
* No database or SQL is used.
* Booking data is temporary and is lost when the program is closed.
* No payment functionality is included.

---

## Future Scope

* Add a graphical user interface using **Tkinter**.
* Add movie names and show timings.
* Add theatre and screen information.
* Add customer details such as name and mobile number.
* Add ticket price calculation.
* Add payment functionality.
* Add a database using MySQL or SQLite.
* Add booking history.
* Generate and store ticket details.
* Add multiple movies and multiple shows.

---

## Conclusion

The Movie Ticket Booking System is a beginner-friendly Python project that demonstrates how basic programming concepts can be used to create a simple real-world application.

The project provides essential seat management features such as viewing available seats, booking seats, cancelling bookings, searching seat status, viewing booked seats, and counting available seats. It provides practical experience with Python functions, lists, loops, conditional statements, and user input.

This project serves as a foundation for developing a more advanced movie ticket booking application with a graphical interface, database, customer management, and payment functionality.
