DBMS ARCHITECTURE(1-LEVEL,2-LEVEL,3-LEVEL)
A DBMS architecture define how users interact with the database to read ,write and upadte the information.A well designed structure and schema ensures consistency and and improve performance.


Types of DBMS Architecture:
A. 1-tier Architecture
B. 2-tier Architecture
C. 3-tier Architecture

1-TIER ARCHITECTURE:
In this architecture ,the users works directly with the databse on the same system.
The client,server and database are on the same application.
The user can directly open the server interact with the database they do not need nay type of differnet server
EX:A common example is Microsoft Excel. Everything from the user interface to the logic and data storage happens on the same device. The user enters data, performs calculations and saves files directly on their computer.

ADVANTAGES:
Simple Architecture: 1-Tier Architecture is the most simple architecture to set up, as only a single machine is required to maintain it.
Cost-Effective: No additional hardware is required for implementing 1-Tier Architecture, which makes it cost-effective.
Easy to Implement: 1-Tier Architecture can be easily deployed and hence it is mostly used in small projects.

DISADVANTAGES:
Limited to Single User: Only one person can use the application at a time. It’s not designed for multiple users or teamwork.
Poor Security: Since everything is on the same machine, if someone gets access to the system, they can access both the data and the application easily.
No Centralized Control: Data is stored locally, so there's no central database. This makes it hard to manage or back up data across multiple devices.
Hard to Share Data: Sharing data between users is difficult because everything is stored on one computer.


2-TIER ARCHITECTURE:
It is similar to client server models. 
The application at the client end directly communicates with the database on the server side. APIs like ODBC and JDBC are used for this interaction. 
The server side is responsible for providing query processing and transaction management functionalities.

ADVANTAGES:
Easy to Access: 2-Tier Architecture makes easy access to the database, which makes fast retrieval.
Scalable: We can scale the database easily, by adding clients or upgrading hardware.
Low Cost: 2-Tier Architecture is cheaper than 3-Tier Architecture and Multi-Tier Architecture.
Easy Deployment: 2-Tier Architecture is easier to deploy than 3-Tier Architecture.
Simple: 2-Tier Architecture is easily understandable as well as simple because of only two components.

DISADVANTAGES:
Limited Scalability: As the number of users increases, the system performance can slow down because the server gets overloaded with too many requests.
Security Issues: Clients connect directly to the database, which can make the system more vulnerable to attacks or data leaks.
Tight Coupling: The client and the server are closely linked. If the database changes, the client application often needs to be updated too.
Difficult Maintenance: Managing updates, fixing bugs, or adding features becomes harder when the number of users or systems increases.



3-TIER ARCHITECTURE:
In 3-Tier Architecture, there is another layer between the client and the server. The client does not directly communicate with the server. 
Instead, it interacts with an application server which further communicates with the database system and then the query processing and transaction management takes place. 
This intermediate layer acts as a medium for the exchange of partially processed data between the server and the client.
This type of architecture is used in the case of large web applications
EX: E-commerce Store

User: You visit an online store, search for a product and add it to your cart.
Processing: The system checks if the product is in stock, calculates the total price and applies any discounts.
Database: The product details, your cart and order history are stored in the database for future reference.

ADVANTAGES:
Enhanced scalability: Scalability is enhanced due to the distributed deployment of application servers. Now, individual connections need not be made between the client and server.
Data Integrity: 3-Tier Architecture maintains Data Integrity. Since there is a middle layer between the client and the server, data corruption can be avoided/removed.
Security: 3-Tier Architecture Improves Security. This type of model prevents direct interaction of the client with the server thereby reducing access to unauthorized data.

DISADVANTAGES:
More Complex: 3-Tier Architecture is more complex in comparison to 2-Tier Architecture. Communication Points are also doubled in 3-Tier Architecture.
Difficult to Interact: It becomes difficult for this sort of interaction to take place due to the presence of middle layers.
Slower Response Time: Since the request passes through an extra layer (application server), it may take more time to get a response compared to 2-Tier systems.
Higher Cost: Setting up and maintaining three separate layers (client, server and database) requires more hardware, software and skilled people. This makes it more expensive.

