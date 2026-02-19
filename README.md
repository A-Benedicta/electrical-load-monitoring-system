Electrical Load Monitoring System
Week 1 Implementation
Overview

This project is a C++ console-based application developed for the Electrical Load Monitoring capstone project.

This stage builds on the Week 1 foundation by introducing data processing and basic analytical features.

At this stage, data is stored temporarily in memory using a vector.

Features Implemented

Defined a struct Appliance to store:

Appliance name

Power rating (Watts)

Usage hours per day

Used vector<Appliance> for dynamic storage

Implemented a menu-driven interface

Implemented appliance registration

Implemented view all appliances feature

Added input validation:

Name must not be empty

Power must be greater than zero

Hours must be between 0 and 24

Program Structure (Week 1)
main.cpp
README.md

How the Program Works

The program displays a menu.

The user selects an option.

The user can register an appliance by entering:

Name

Power rating

Usage hours per day

Registered appliances are stored in a vector.

The user can view all registered appliances.

The program runs until the user chooses Exit.

Sample Menu
1. Register appliance
2. View all appliances
0. Exit

Objective of Week 1

The objective of Week 1 is to establish the foundation of the system before adding energy calculations, billing, and file persistence in later weeks.