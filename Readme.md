# Hotel Reservation System

The **Hotel Reservation System** is a Java application designed to handle hotel bookings efficiently while demonstrating the core principles of **Object-Oriented Programming (OOP)**. This project provides a modular, reusable, and extendable structure for managing reservations, customers, and room availability.

---

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [OOP Principles in Action](#oop-principles-in-action)
4. [Project Structure](#project-structure)
5. [How to Run](#how-to-run)
6. [Team Members](#team-members)
---

## Features
- **Room Management**: Add, update, and remove room details.
- **Customer Management**: Handle customer information and reservations.
- **Booking System**: Reserve rooms with real-time updates.
- **Data Validation**: Ensure accurate input for smooth operation.
- **Scalability**: Easy to extend functionality for additional features like payment integration.

---

## Technologies Used
- **Programming Language**: Java
- **IDE**: IntelliJ IDEA
- **Version Control**: Git and GitHub

---

## OOP Principles in Action
This project is designed with a focus on the four main principles of OOP:
1. **Encapsulation**:  
   - All class attributes are private and accessed via getter and setter methods.  
   - Ensures that the internal state of objects is well-protected.

2. **Abstraction**:  
   - Abstract classes and interfaces are used to define shared behavior while hiding implementation details.

3. **Inheritance**:  
   - Base classes such as `Person` are extended by more specific classes like `Customer`.  
   - Promotes code reuse and logical hierarchy.

4. **Polymorphism**:  
   - Methods are overridden to allow specific behaviors in derived classes.  
   - Example: A `Room` class might override a `getPrice()` method based on room type.

---

## Project Structure
The project is organized into packages and classes for better maintainability:
```
src/
│
├── models/
│   ├── Room.java
│   ├── Customer.java
│   ├── Reservation.java
│
├── services/
│   ├── RoomService.java
│   ├── ReservationService.java
│   ├── CustomerService.java
│
├── utils/
│   ├── InputValidator.java
│   ├── DateUtils.java
│
└── Main.java
```
- **`models/`**: Contains the core entities of the application.  
- **`services/`**: Provides the logic for managing data and operations.  
- **`utils/`**: Contains helper classes for validation and utilities.  
- **`Main.java`**: Entry point of the application.

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/Mina-Demyann/HotelReservation_OOP.git
   ```
2. Open the project in your preferred Java IDE.
3. Compile and run the `Main.java` file.
4. Follow the on-screen instructions to explore the reservation system.

---

## Team Members
This project was collaboratively developed by:
- **Mina Demyan**
- **Nasser-Hana**
- **Barhoma**
- **Poula**
- **Loay**
- **Micheal**

---


## Acknowledgments
This project was built as a demonstration of **Object-Oriented Programming** skills and Java expertise. Contributions and feedback are welcome!

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
