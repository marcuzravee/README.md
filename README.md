✈️ Airline Check-in & Boarding System

Description

The Airline Check-in & Boarding System is a Java console application that simulates how passengers are handled in an airport. It focuses on the basic flow of passenger management from check-in to boarding while showing how different data structures work in real-life situations.

The system allows the user to:
* Register new passengers
* Simulate check-in lines
* Assign and change seats
* Perform priority boarding
* Search and delete passengers
* View system logs

This project was created to demonstrate understanding of data structures such as arrays, queues, stacks, linked lists, heaps, and binary search trees. 
All structures are manually coded without using Java Collections.

Instructions:

Setup
1. Open the project folder in your IDE or text editor.
2. Locate the file:

app/Main.java
1. Right click and run the file, or use terminal commands:

javac app/Main.java
java app.Main
Once opened, the main menu will appear.

Passenger Management
1. Add Passenger
Select option 1 to add a new passenger. You will input:
* PNR
* Last Name
* Zone
* Tier
The passenger will automatically be placed into all necessary systems like array, queue, priority queue, BST, and logs.

2. Display Passengers
Select 2 to show all stored passengers from the array.
This helps check if data was correctly entered.

3. Sorting Demonstration
Select 3 to view sorting results:
* Bubble Sort (by last name)
* Insertion Sort (by PNR)
* Selection Sort (by Zone)
This shows how the same data changes order using different algorithms.

Check-in Process
4. Queue Check-in Simulation
Choosing 4 simulates the airport check-in line.
Options include:
1. Dequeue one passenger
2. Dequeue all passengers
3. Test underflow
This uses FIFO logic, meaning the first passenger added is the first served.

Seat Management
5. Stack Seat Undo/Redo
This option allows seat changes for a passenger.
The user enters a PNR and new seat, then chooses:
* Undo (revert previous seat)
* Redo (reapply seat)
This uses two stacks to track changes using LIFO behavior.

Boarding Simulation
6. Priority Queue Boarding
This option boards passengers based on priority using a binary heap.
Passengers with higher tier and zone are processed first, similar to real airline VIP boarding.

Passenger Search
7. BST Search/Delete
This option allows searching passengers using their PNR.
If found, the user can choose to delete the record from the BST.
This demonstrates efficient searching using Binary Search Tree logic.

Logs and Records
8. Linked List Logs
Displays:
* Baggage Log (Singly Linked List)
* Gate Timeline (Doubly Linked List)
You can also add new gate change entries which update the log.

How the System Works
1. Passenger is added.
2. Data is stored in array, queue, heap, BST, and logs.
3. User can perform different operations using the main menu.
4. All actions reflect actual airport procedures like:
    * Lining up
    * Boarding priority
    * Seat correction
    * Passenger tracking
This gives a realistic and educational simulation.

References
* Data Structures & Algorithms Lecture Notes
* Java Programming Materials
* Instructor Discussions
* Airline System Concepts

