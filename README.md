# 🎬 Movie Ticket Booking System

A C++ console application for managing movie ticket bookings, built with OOP principles. Features include movie selection, seat booking, pricing, membership benefits, and admin controls.

## 🌟 Features

- **User-Friendly Menu System**
  - Book tickets
  - View bookings
  - Check prices
  - View available seats
  - Check movie timings
  - Membership registration

- **Core Functionalities**
  - Movie selection (4 pre-loaded films)
  - Seat availability tracking (300 seats max)
  - Ticket types (Gold/Silver with different pricing)
  - Membership benefits (10% discount)

- **Admin Features**
  - Secure login system
  - Movie management
  - Booking oversight

## 🛠️ Technologies Used

- **Language:** C++
- **Libraries:**
  - `<iostream>` for I/O
  - `<fstream>` for file operations
  - `<conio.h>` for `getch()`
- **OOP Concepts:**
  - Classes and Inheritance
  - Encapsulation
  - Polymorphism

## 📋 Class Structure

| Class | Description |
|-------|-------------|
| `Menu` | Handles UI and navigation |
| `Person` | Base class for personal info |
| `Customer` | Extends Person with booking features |
| `Login` | Manages admin authentication |
| `Movie` | Stores film details and showtimes |
| `Time` | Manages screening schedules |
| `Ticket` | Handles booking logic and pricing |

## 🚀 How to Run

1. **Prerequisites:**
   - C++ compiler (g++ recommended)
   - Windows OS (for `conio.h` compatibility)

2. **Compilation:**
   ```bash
   g++ main.cpp -o MovieBookingSystem
3. Execution:
   ```bash
   ./MovieBookingSystem

📝 Usage Instructions
Admin login (stored in login.txt)

Select movies from available options

Choose ticket type (Gold/Silver)

View available seats

Complete booking with personal details

🤝 Contributing
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

👨‍💻 Developers

I have edone this project in contribution with classmate
**Taha Naveed**
