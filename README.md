# Extreme Events Booking System

A C# Windows Forms application simulating an event booking system for a company called **Extreme Events**. This project demonstrates multi-form interactions, login validation, array-based data handling, and basic business logic implementation.

---

## Features

- **Login System**
  - Two user types: Admin and Fan
  - Password validation with limited attempts
  - Navigation between forms based on login type

- **Admin Form**
  - Add event names and VIP ticket prices
  - Stores data in arrays accessible across forms

- **Booking Form**
  - Choose event, date, number of tickets, city, and seating type
  - Optional extras: programme or limo service
  - Calculates total cost based on ticket type and extras
  - Displays confirmation message with formatted date

- **Data Handling**
  - Arrays store event names and VIP prices
  - ComboBox dynamically loads events from Admin input
  - Validates inputs such as date (7+ days in advance), number of tickets, and selections

- **Date Functionality**
  - Display multiple date formats
  - Compare and manipulate dates

---

## Technologies Used

- C# with Windows Forms
- Visual Studio IDE
- .NET Framework
- Basic array and form handling
- Event-driven programming

---

## How to Run

1. Clone the repository or download the project zip.
2. Open the `.sln` solution file in **Visual Studio**.
3. Build the solution to restore dependencies.
4. Run the project and start with the **Login Form**.

---

## Screenshots

*(Add screenshots of Login, Admin, and Booking forms here if possible)*

---

## Notes

- This is a mini-project created as part of the Information Systems IIA course at the University of the Witwatersrand (2023).  
- Designed for learning purposes, showcasing form navigation, array usage, and input validation in C# Windows Forms.

---

