# Smart Parking Management System

A Java-based Smart Parking Management System developed using Object-Oriented Programming (OOP), Java Swing, JDBC, and MySQL.

## Features

- **Vehicle Management:** Register cars and bikes using vehicle numbers and mobile numbers.
- **Live Parking Layout:** View available and occupied parking slots.
- **Automatic Slot Allocation:** Assign available slots based on vehicle type.
- **Vehicle Search:** Find a parked vehicle using its vehicle number and registered mobile number.
- **Parking Fee Calculation:** Calculate parking charges based on parking duration.
- **Payment Confirmation:** Confirm payment and release the parking slot.
- **Parking History:** View completed parking sessions and payment details.
- **Revenue Tracking:** Display total revenue from paid parking sessions.
- **Database Integration:** Store active vehicles and parking history in MySQL.
- **Data Persistence:** Restore active vehicles and previous paid parking sessions when the application restarts.

## Technologies Used

- Java
- Java Swing
- Object-Oriented Programming (OOP)
- JDBC
- MySQL
- NetBeans IDE
- Git and GitHub

## Parking Rates

| Vehicle Type | Rate per Hour |
|---|---:|
| Car | ₹50 |
| Bike | ₹20 |

Parking duration is rounded up to the next billable hour, with a minimum charge of one hour.

## Project Structure

```text
oop-project/
├── src/
│   └── oop/
│       └── project/
│           ├── Bike.java
│           ├── Car.java
│           ├── DatabaseManager.java
│           ├── MainFrame.java
│           ├── OopProject.java
│           ├── ParkingManager.java
│           ├── ParkingSlot.java
│           └── Vehicle.java
├── nbproject/
├── build.xml
├── manifest.mf
└── README.md
```

## Database Setup

1. Install MySQL Server and start the MySQL service.
2. Create a database named `smart_parking`.
3. Add the MySQL Connector/J library to the Java project.
4. Configure the `SMART_PARKING_DB_PASSWORD` environment variable with your MySQL password.
5. Ensure the database connection settings in `DatabaseManager.java` match your local MySQL configuration.

The application initializes the required parking tables when it connects to the database.

## How to Run

1. Install the JDK, MySQL Server, and NetBeans IDE.
2. Clone or download this repository.
3. Open the project in NetBeans.
4. Add the MySQL Connector/J library if it is not already configured.
5. Set the `SMART_PARKING_DB_PASSWORD` environment variable.
6. Run `OopProject.java` to launch the application.

## Developed For

An Object-Oriented Programming project demonstrating Java classes, inheritance, abstraction, GUI development, JDBC connectivity, and MySQL database operations.
