Electrical Load Monitoring System
Week 4 Implementation
Overview

In Week 4, file persistence and report export functionality were implemented. The system now saves appliance data to a file and automatically loads existing data when the program starts.

Additionally, billing reports are exported to a text file for record keeping.

This stage completes the core functionality of the Electrical Load Monitoring System.

Features Implemented in Week 4

Save appliance data to appliances.txt

Load appliance data automatically at program startup

Export billing report to billing_summary.txt

File parsing using stringstream

Error handling for file operations

Files Used
appliances.txt

Stores appliance data in the format:

Name|PowerW|HoursPerDay
Fan|75|8
TV|120|5

billing_summary.txt

Stores generated billing report including:

Individual appliance daily cost

Total daily energy

Total daily cost

Monthly energy estimate

Monthly cost estimate

Technical Concepts Applied

<fstream> for file reading and writing

<sstream> for parsing file content

Data validation when loading from file

Persistent data storage

Report generation and export

Updated Menu (Week 4)
1. Register appliance
2. View all appliances
3. Search appliance by name
4. Energy summary (kWh/day)
5. Billing summary (save to file)
0. Exit

Project Structure (Final Version)
main.cpp
appliances.txt
billing_summary.txt
README.md
.gitignore

Objective of Week 4

The objective of Week 4 is to implement permanent data storage and export functionality, ensuring that appliance data is not lost when the program closes and billing reports can be saved for future reference.