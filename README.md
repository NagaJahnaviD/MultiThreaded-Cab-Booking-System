# Concurrent Cab Booking System

## Overview
This project is a simple simulation of a concurrent cab booking system, demonstrating how multiple users can book cabs simultaneously. The system showcases the use of **multithreading** and **synchronization** in **Java** to handle concurrent requests and simulate cab allocation based on availability.

The user interface is basic, built using **Java AWT** (Abstract Window Toolkit), which provides a simple way to interact with the system. The system runs as a **multi-threaded application**, simulating how cabs are allocated to users in real-time.

## Key Features
- **Simulated Cab Booking**: Multiple users can request cab bookings simultaneously.
- **Threading & Synchronization**: Demonstrates the handling of concurrent booking requests.
- **Basic User Interface**: Built using **Java AWT** for simplicity and functionality.
- **MySQL Integration**: A `cabs.sql` file is included for setting up the database schema for cab availability and booking.

## How to Run
1. **Setup Database**:  
   Import the `cabs.sql` file into your **MySQL** database to create the necessary tables.
   
2. **Compile and Run**:  
   - Clone the repository.  
   ```bash
   git clone <repository-url>
   cd Concurrent-Cab-Booking-System
   javac Main.java
   java Main

**Limitations**
Simulation Purposes: This project is a basic simulation and does not reflect real-world cab booking systems.
Basic UI: The user interface is minimal and not intended for practical use in production environments.
Concurrency Handling: Demonstrates threading and synchronization concepts but lacks scalability and performance optimization.
**Note**
This project aims to showcase my understanding of Java multithreading and synchronization. It is a learning exercise and can not be used as a production system.