**Python & MySQL Projects**

A collection of three beginner-friendly Python projects demonstrating Python programming, MySQL database connectivity, CRUD operations, searching, updating, and data management.

__1. Molecular Database__

A command-line drug and chemical information management system built with Python and MySQL.

Features-

    Create and connect to a MySQL database
    Store molecular/compound information
    View all records
    Add new compounds
    Search compounds
    Advanced search by:
    Compound name
    Formula
    Price
    Side effects
    Applications
    Occurrence
    Chemical nature
    Update records
    Delete records

Data Stored-

    Each compound contains:
    
    Compound Name
    Molecular Formula
    Applications
    Occurrence — Natural/Artificial
    Side Effects
    Price
    Chemical Nature — Acidic/Basic/Neutral

Technologies-

    Python
    MySQL
    mysql-connector-python

__2. Indian Cricket & T20 World Cup Team Database__

A Python and MySQL-based cricket team information system.

The project manages player information for the Indian cricket team and provides information about selected T20 World Cup 2022 teams.

Features-

    Add player records
    Display player records
    Search for players
    Update player details
    Delete player records
    Display players by role:
    Batsman
    Bowler
    All-rounder
    Wicketkeeper
    Display players below 30 years of age
    View information for different T20 World Cup teams

Player Data-

    Name
    Role
    Jersey Number
    Age
    Number of ODI matches / status

Teams Included-

    India
    England
    Sri Lanka
    Australia
    New Zealand
    Pakistan
    South Africa
    West Indies

Technologies-

    Python
    MySQL
    mysql-connector-python

__3. JAVT Tours and Travels__

A Tourist Information System built with Python and MySQL for managing traveller preferences and tour information.

Features-

    Tourist registration
    Destination selection
    Food preference selection
    Accommodation preference
    Translator requirement
    Entertainment preferences
    Transport preferences
    Temperature information
    Package recommendations
    Clothing recommendations based on temperature
    Emergency and transport service information
    Random discounts between 5% and 20%
    View registered tourists
    Search tourist records

Destinations-

    J&K, Goa, Paris, Maldives, London, Moscow, Egypt, Bali, Istanbul, and Dubai.

Food Options-

    Vegetarian
    Non-vegetarian
    Jain
    Buddhist

Database-

    The project uses a MySQL database named javt_tours with tables for:
    
    tourists
    destinations
    food_preferences

Technologies-

    Python
    MySQL
    mysql-connector-python


__Installation__

1) Install the MySQL connector:

        pip install mysql-connector-python

Make sure MySQL Server is running before starting the database-based projects.

2) Update the database configuration with your own local MySQL credentials:

        DB_HOST = "localhost"
        DB_USER = "YOUR_MYSQL_USERNAME"
        DB_PASSWORD = "YOUR_MYSQL_PASSWORD"

Do not commit your actual MySQL password to GitHub.

📁 Project Structure
Python-MySQL-Projects/
│
├── Molecular-Database/
│   └── molecular_database.py
│
├── Cricket-Team-Database/
│   └── cricket_database.py
│
├── JAVT-Tours-and-Travels/
│   ├── javt_tours.py
│   └── schema.sql
│
└── README.md

__Purpose__

    These projects were created to practice Python, MySQL connectivity, database management, CRUD operations, SQL queries, functions, conditional logic, and command-line application development.
