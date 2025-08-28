
# Hotel Management System (Java)

A simple console-based **Hotel Management System** written in Java. This program allows you to manage basic hotel bookings such as adding, displaying, and canceling room bookings.

---

## Features

* Add a booking with guest name, room number, and number of days stayed
* Display all current bookings along with the total bill
* Cancel a booking by room number
* Simple text-based menu for easy interaction
* Fixed room rate billing calculation

---

## How to Run

1. Clone or download this repository.

2. Compile the program using:

   ```bash
   javac HotelManagement.java
   ```

3. Run the compiled program:

   ```bash
   java HotelManagement
   ```

4. Follow the on-screen menu to manage bookings.

---

## Code Overview

* **Booking class:** Represents a booking with guest info, room number, days stayed, and bill calculation.
* **HotelManagement class:** Contains main menu and methods to add, display, and cancel bookings stored in an `ArrayList`.

---

## Sample Usage

```plaintext
Hotel Management System
1. Add Booking
2. Display Bookings
3. Cancel Booking
0. Exit
Enter your choice: 1
Enter guest name: Alice Smith
Enter room number: 201
Enter number of days stayed: 4
Booking added successfully.

Hotel Management System
1. Add Booking
2. Display Bookings
3. Cancel Booking
0. Exit
Enter your choice: 2
Current Bookings:
Room: 201, Guest: Alice Smith, Days: 4, Bill: $400
```

---

## Requirements

* Java JDK 8 or above
* Basic knowledge of running Java programs from the terminal/command prompt


