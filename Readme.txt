This project is a User Management System built using Object-Oriented Programming (OOP) in PHP. 
It demonstrates clean architecture and core OOP principles such as abstraction, inheritance, interfaces, traits, and polymorphism.

The Structure of file
/user-management/
│── /App/
│    ├── /Core/
│    │    ├── AbstractUser.php
│    │    ├── AuthInterface.php
│    │    ├── LoggerTrait.php
│    │
│    ├── /Models/
│    │    ├── Admin.php
│    │    ├── RegularUser.php
│    │
│    ├── /Services/
│    │    ├── AuthService.php
│
│── index.php
│── autoload.php

How it works?
1. Users are created with hashed passwords
2. Authentication is handled via AuthService
3. The system validates login credentials
4. Admin users log activity using a trait
5. Different behaviors are handled via polymorphism

