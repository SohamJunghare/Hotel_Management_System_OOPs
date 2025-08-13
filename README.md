# Hotel Management System (Java Console App)

## Overview
This is a Java-based console application for managing hotel operations like room booking, food ordering, and customer checkout.  
It supports multiple room categories, maintains customer records, generates bills, and saves all data persistently using file serialization.  
When restarted, the program restores the previous state from the saved backup file.

## Features
- **Room Categories**:
  - Luxury Double Room
  - Deluxe Double Room
  - Luxury Single Room
  - Deluxe Single Room
- **Booking System**:
  - Shows available rooms
  - Records customer details
  - Prevents double booking
- **Food Ordering**:
  - Fixed menu with set prices
  - Multiple items and quantities allowed
- **Billing**:
  - Calculates total cost (room + food)
  - Displays detailed bill
- **Data Persistence**:
  - Saves all hotel data in `backup` file
  - Loads data automatically on restart

## Technology Used
- Java SE (Core Java)
- Object-Oriented Programming (Inheritance, Encapsulation, Polymorphism)
- Collections (ArrayList)
- Serialization (ObjectInputStream, ObjectOutputStream)
- Multithreading for background file saving

## How to Run
1. Save all `.java` files in a single folder.
2. Compile:  
   `javac Main.java`
3. Run:  
   `java Main`
4. Use the menu options to manage bookings, orders, and checkouts.

## Menu Options
1. Display Room Details  
2. Display Availability  
3. Book Room  
4. Order Food  
5. Checkout  
6. Exit

## Food Menu
1. Sandwich - ₹50  
2. Pasta - ₹60  
3. Noodles - ₹70  
4. Coke - ₹30
