#  Cab Booking System (C++)

## Project Overview
This project implements a Cab Booking System using C++ and fundamental data structures. 
It simulates ride-hailing operations including driver management, ride requests, shortest path calculation, and ride history tracking.

## 1 Data Structures Used

### Binary Search Tree (BST)
Used for efficient driver management:
Insert Driver
Remove Driver
Search Driver
In-order traversal (sorted output)

### 2 Linked List
Used to store ride history:
O(1) insertion
Reverse chronological order
Ride completion & cancellation tracking

### 3️ Queue (FIFO)
Used for pending ride requests when no driver is available.

### 4️ Graph (Adjacency Matrix)
Represents city map with weighted edges.

### 5️ Dijkstra’s Algorithm
Used to:
- Find shortest path
- Assign nearest available driver
- Calculate fare based on distance

---

##  Features
- Add / Remove / Update Drivers
- Request Ride
- Auto-assign nearest driver
- Cancel Ride
- Complete Ride
- Process Pending Requests
- View Ride History
- Display City Map

---

##  Technologies Used
- C++
- Object-Oriented Programming
- Manual Implementation of Data Structures (No STL)

---

##  System Architecture
Graph → Shortest Path  
BST → Driver Selection  
Queue → Pending Requests  
Linked List → Ride History  

---


---

##  Learning Outcomes
- Strong understanding of BST, Linked List, Queue and Graph
- Implementation of Dijkstra Algorithm
- OOP design principles
- Integration of multiple data structures in one system

---

## Author
Waleed Asif  
Mechatronics Engineering Student
