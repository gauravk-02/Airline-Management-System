# Airline Management System

## Overview
The Airline Management System automates the registration process of an airline, managing tasks such as storing and retrieving passenger information, handling flight details, and managing booking records. The system also facilitates various transactions related to air travel. The backend is powered by a MySQL database, while the frontend is developed using Java Core with Swing for the user interface. This system is designed to manage multiple entities, including airlines, airline employees, and customers, through a structured database schema.

## Features
- **Passenger Management:** Store, retrieve, and manage passenger information.
- **Flight Management:** Handle flight details, including adding, updating, and deleting records.
- **Booking Management:** Manage ticket reservations, cancellations, and payment details.
- **Database Management:** Utilize MySQL to store and manage all airline-related data efficiently.

## Technology Stack
- **Language:** Java Core
- **GUI Framework:** Swing
- **IDE:** NetBeans 8.2
- **Database:** MySQL
- **Operating System:** Windows 10

## Project Structure
- **Backend:** Implements MySQL database for data storage, handling tables such as `cancellation`, `flight`, `login`, `passenger`, `payment`, `reservation`, and `sector`.
- **Frontend:** Uses Java Swing to create the user interface, including features like dropdown menus and forms for managing airline operations.
- **Mainframe Class:** A centralized class managing the entire application, including initializing the interface and handling user actions.

## Installation and Setup

### Software Requirements
- **Operating System:** Windows 10
- **Java:** JDK 8
- **IDE:** NetBeans 8.2
- **Database:** MySQL

### Steps to Set Up
1. **Install Java JDK 8:** Ensure Java is installed and set up correctly.
2. **Install MySQL:** Set up the MySQL database and create the necessary tables.
3. **Clone the Repository:**
    ```bash
    git clone https://github.com/gauravk-02/airline-management-system.git
    ```
4. **Open in NetBeans:** Open the project in NetBeans 8.2.
5. **Configure the Database:** Set up the database connection in the project settings.
6. **Run the Application:** Execute the main class `Mainframe.java` to start the application.

## Implementation Details
- **Backend Implementation:** Detailed SQL scripts are provided to create necessary tables and manage data.
- **Frontend Implementation:** Java Swing components are used to create a user-friendly interface with functionalities like flight information, customer management, payment processing, and cancellations.

## Conclusion
The Airline Management System automates various aspects of airline management, providing an efficient, accurate, and reliable system for handling passenger and flight data. This project explores key areas of computer science and software development, particularly in building robust and scalable applications.
