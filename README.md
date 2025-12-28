##RESTFUL-API-DEVELOPMENT

*COMPANY NAME*:CODTECH IT SOLUTIONS

*NAME*:G.PAVITHRA

*INTERN ID*:CT04DR3094

*DOMAIN*:SOFTWARE DEVELOPMENT

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH

##DESCRIPTION OF RESTFUL API DEVELOPMENT

1. Introduction to the Task
The primary objective of this project was to design and implement a functional RESTful API (Application Programming Interface) for managing a library’s book inventory. In modern software development, a REST API serves as the bridge between a data layer and the user interface. By following the Representational State Transfer (REST) architectural style, this system ensures that communication between the client and the server is standardized and stateless. The system was built using the Node.js runtime environment and the Express.js framework.

2. Architectural Design and Principles
The development of this API was guided by core REST constraints to ensure professional quality:

Statelessness: Every request from the client contains all necessary information for the server to process it, improving reliability.

Uniform Interface: By using standard HTTP verbs, the API becomes intuitive for other developers.

Resource-Based Routing: The API uses a clean, noun-based structure, such as /api/books, to represent the collection of resources.

3. Implementation of CRUD Operations
The heart of the system is the implementation of CRUD (Create, Read, Update, Delete) operations:

CREATE (POST): Users can add new titles to the inventory via a JSON object.

READ (GET): This allows users to list all books or fetch a specific book using its unique ID.

UPDATE (PUT): This allows for the modification of existing records, such as changing a book's availability.

DELETE (DELETE): This removes a specific resource from the system entirely.

4. The Development Workflow in VS Code
The implementation process involved setting up a professional development environment in Visual Studio Code (VS Code):

Environment Setup: The first step was installing Node.js and ensuring npm was accessible via the system’s PATH.

Project Initialization: Using npm init -y, a package.json file was generated to manage dependencies.

Dependency Management: The Express framework was installed via the terminal to handle high-level routing efficiently.

Coding and Logic: A server.js file was created to house the logic, including middleware to parse JSON data and defining resource routes.

Testing: The server was launched using node server.js and verified using tools like Thunder Client to confirm correct HTTP status codes.

5. Conclusion
While the current version uses an in-memory array, it provides the logical blueprint for a production-level system. Future iterations could include persistent storage like MongoDB and security layers such as JWT to protect book records. This project successfully demonstrates the ability to translate business requirements into a technical software solution using modern web technologies.


##OUTPUT

<img width="1033" height="512" alt="s1" src="https://github.com/user-attachments/assets/fcf886b6-83bb-458a-99a4-f393a6633896" />

<img width="1027" height="270" alt="s2" src="https://github.com/user-attachments/assets/061d59c0-e3e9-4b7a-a907-db26d6fb9d01" />

<img width="640" height="227" alt="s3" src="https://github.com/user-attachments/assets/7136dd61-5569-40a1-af5a-891db83aa2fa" />

<img width="1036" height="611" alt="s4" src="https://github.com/user-attachments/assets/703b62b3-47a7-49be-98b1-6bf64a71a3e3" />





