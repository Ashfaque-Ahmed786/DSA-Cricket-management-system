🏏 Cricket Management System (Group C — Queue)
📘 Project Overview

This project is a Cricket Management System implemented using the Queue data structure in Java.
It allows adding, updating, deleting, viewing, and processing player records in FIFO (First In, First Out) order.
The project was developed as part of the Data Structures and Algorithms (DSA) course to demonstrate efficient data organization and manipulation.

🎯 Objective

The main goal of this project is to:

Apply DSA concepts in real-world scenarios.

Use Queue operations (Enqueue, Dequeue) for managing inventory data.

Implement complete CRUD operations using queue logic.

Build a simple, easy-to-use console application for cricket player management.

🧱 Data Structure Used: Queue
Operation	Description
enqueue()	Add a new player to the queue (rear).
dequeue()	Remove a player from the queue (front).
display()	Show all players in queue order.
updateById()	Update an existing player’s details.
deleteById()	Delete a player from the queue by ID.
⚙️ Features / CRUD Operations

Create: Add a new player to the system.

Read: View all players currently in the queue.

Update: Modify player details using their ID.

Delete: Remove a specific player or dequeue the front player.

💻 Technologies Used

Programming Language: Java

IDE: NetBeans / IntelliJ IDEA

Concepts: Queue, Linked List, Object-Oriented Programming (OOP)

🚀 How to Run

Open the project in NetBeans (or any Java IDE).

Add three files in the same package:

Player.java

PlayerQueue.java

CricketManagementSystem.java

Run the CricketManagementSystem.java file.

Use the console menu to perform CRUD operations.

🧾 Sample Output
===== Cricket Management System (Queue) =====
1. Add Player
2. View All Players
3. Update Player by ID
4. Delete Player by ID
5. Dequeue Player
6. Exit

Players in Queue (front → rear):
[ID:101 | Ahmed Ali | Age:21 | Batsman | 0300-1112223]
[ID:102 | Bilal Khan | Age:23 | Bowler | 0300-2223334]
[ID:103 | Cyrus Shah | Age:20 | Allrounder | 0300-3334445]

📂 Project Structure
com.mycompany.cricketmanagementsystem/
│
├── Player.java              # Player class (data model)
├── PlayerQueue.java         # Queue implementation (CRUD logic)
└── CricketManagementSystem.java  # Main file with menu

🧑‍💻 Contributors

Group C – Queue Implementation
Department of Software Engineering
Mehran University of Engineering & Technology (MUET), SZAB Campus
