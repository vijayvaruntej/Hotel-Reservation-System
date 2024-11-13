# Hotel Reservation System

A Java-based hotel reservation system that allows users to manage room reservations in a MySQL database. This application supports basic CRUD operations (Create, Read, Update, Delete) for handling hotel room reservations and is intended to demonstrate how to interact with a relational database using Java.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contribution](#contribution)
- Happy Booking

## Features

- **Reserve a Room**: Create a new reservation by specifying guest details and room number.
- **View Reservations**: Display all current reservations, including guest names, room numbers, and contact information.
- **Get Room Number**: Retrieve the room number for a specific reservation based on guest details.
- **Update Reservation**: Modify reservation information such as guest name, room number, and contact number.
- **Delete Reservation**: Remove an existing reservation from the database.
- **User-Friendly CLI Interface**: Simple text-based interface for navigating reservation options.

## Technologies Used

- **Java**: Core programming language used for developing the application.
- **MySQL**: Relational database management system to store and manage reservation data.
- **JDBC (Java Database Connectivity)**: Interface for connecting Java applications to the MySQL database.


## Setup

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/prabhatthakuryt/Hotel-Reservation-System.git

2. Configure your MySQL database settings in the HotelReservationSystem.java file:
   ```
   private static final String DB_URL = "jdbc:mysql://localhost:3306/hotel_db";
   private static final String DB_USER = "your_username";
   private static final String DB_PASSWORD = "your_password";

3. Compile and run the application
4. Follow the on-screen menu options to use the system.

## Usage
- Upon running the application, you'll be presented with a menu to choose your desired operation (reservation, viewing, editing, or exiting).

- Follow the prompts to input reservation details, view current reservations, edit existing bookings, and more.

## Contribution
- Contributions are welcome! Feel free to open issues and pull requests for bug fixes, enhancements, or new features.

## Happy Booking
