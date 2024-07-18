# Bus Reservation System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction
The Bus Reservation System is a console-based application that allows administrators and customers to manage bus bookings. Administrators can add new buses and confirm customer tickets, while customers can book, view, and cancel their bus tickets.

## Features
- **Admin Login**
  - Add new buses.
  - Confirm customer tickets.
  - View all bookings.
- **Customer Login/Signup**
  - Book bus tickets.
  - Cancel bus tickets.
  - View the status of booked tickets.

## Technologies Used
- **Java**: The main programming language used to build the application.
- **ConsoleColors**: A utility to print colored text in the console for better user experience.

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/bus-reservation-system.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd bus-reservation-system
    ```
3. **Compile the Java files:**
    ```bash
    javac -d bin src/com/bus/main/Main.java
    ```
4. **Run the application:**
    ```bash
    java -cp bin com.bus.main.Main
    ```

## Usage
1. **Running the Application:**
   - Execute the main class (`Main.java`) to start the application.
   - Choose to login as either an Administrator or a Customer.

2. **Administrator:**
   - Login with the provided credentials.
   - Use the menu to add buses, confirm tickets, or view all bookings.

3. **Customer:**
   - Login or sign up for a new account.
   - Use the menu to book, view, or cancel tickets.

## Code Overview
- **Main.java**: The entry point of the application. Contains methods to handle user choices and direct to appropriate functionalities.
- **ConsoleColors.java**: A utility class for adding colors to console outputs.
- **usecases package**: Contains various use case classes for handling specific operations like adding buses, booking tickets, etc.
- **bean package**: Contains the `Customer` class which represents a customer in the system.

## Contributors
- [Tameem Shaikh](https://github.com/tamim-c)
