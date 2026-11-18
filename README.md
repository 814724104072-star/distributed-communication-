Distributed Communication Network Model
Project Overview
This project demonstrates communication between distributed processes using different message-passing techniques. It simulates how processes exchange messages in a distributed communication network.
Objectives
To understand communication between distributed processes.
To implement message-passing communication primitives.
To demonstrate synchronous and asynchronous communication.
To implement point-to-point and broadcast communication.
To understand message sending and receiving using queues.
Technologies Used
Programming Language: Python 3
Concepts: Distributed Computing, Message Passing, Communication Primitives
Tools: Visual Studio Code / Python IDLE
Features
Point-to-Point Communication: Sends a message from one process to another.
Synchronous Communication: Demonstrates message sending with acknowledgement.
Asynchronous Communication: Sends messages without waiting for acknowledgement.
Broadcast Communication: Sends a message from one process to all other processes.
Message Queues: Stores messages until the receiving process collects them.
Sequence Numbers: Identifies the order of messages.
Project Structure
Distributed-Communication-Network/
│
├── distributed_communication_simulator.py
├── README.md
├── distributed_architecture.png
└── communication_workflow.png

How to Run the Project
Step 1: Install Python
Install Python 3 on your computer.
Step 2: Download the Project
Clone the repository:
git clone <your-github-repository-link>

Step 3: Open the Project Folder
Open the downloaded folder in VS Code or any Python editor.
Step 4: Execute the Program
Run the following command:
python distributed_communication_simulator.py

Expected Output
The program demonstrates:
Process creation
Point-to-point message transmission
Synchronous communication
Asynchronous communication
Broadcast message transmission
Message receiving and status display
Working Principle
The model contains three processes: P1, P2 and P3. Each process communicates through message-passing operations. Messages are stored in individual inbox queues and received by the destination process. Sequence numbers help identify the order of messages.
Limitations
This project is a simulation of distributed communication. It demonstrates message-passing concepts within a single Python program and does not perform actual communication over a computer network.
Conclusion
The Distributed Communication Network Model successfully demonstrates different communication primitives and message-passing scenarios. It helps understand how distributed processes exchange information using synchronous, asynchronous, point-to-point and broadcast communication.
NAME
Keerthana S – 814724104072

Department of Computer Science and Engineering
SRM TRP Engineering College, Tiruchirappalli
Academic Year: 2026–2027