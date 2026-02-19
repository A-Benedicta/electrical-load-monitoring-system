Electrical Load Monitoring System
Week 2 Implementation
Overview

In Week 2, additional functionality was added to the Electrical Load Monitoring System. The system now performs energy calculations and allows users to search for appliances by name.

This stage builds on the Week 1 foundation by introducing data processing and basic analytical features.

Features Implemented in Week 2

Energy calculation for each appliance using the formula:

Energy (kWh/day) = (Power × Hours) / 1000


Energy summary display showing:

Individual appliance energy consumption

Total energy consumption per day

Case-insensitive search feature:

Users can search for appliances by name

Implemented using transform() and tolower()

Improved input validation

Technical Concepts Applied

Member function inside struct (energyKWhPerDay())

String manipulation using:

<algorithm>

<cctype>

Case-insensitive comparison

Formatted output using <iomanip>

Updated Menu (Week 2)
1. Register appliance
2. View all appliances
3. Search appliance by name
4. Energy summary (kWh/day)
0. Exit

Objective of Week 2

The objective of Week 2 is to enhance the system by introducing energy computation and search functionality, preparing the system for billing features in Week 3.