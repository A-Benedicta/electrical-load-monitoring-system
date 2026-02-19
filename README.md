Electrical Load Monitoring System
Week 3 Implementation
Overview

In Week 3, the billing system was implemented. The system now calculates electricity cost based on user-input tariff values.

This stage extends the energy computation feature by introducing cost estimation for both daily and monthly usage.

Features Implemented in Week 3

User input for electricity tariff (per kWh)

Daily electricity cost calculation

Monthly electricity cost estimation (30 days)

Billing summary display

Input validation for tariff (must be positive number)

Billing Formulas Used
Daily Energy
Energy (kWh/day) = (Power × Hours) / 1000

Daily Cost
Daily Cost = Total kWh/day × Tariff

Monthly Cost
Monthly Cost = Daily Cost × 30

Updated Menu (Week 3)
1. Register appliance
2. View all appliances
3. Search appliance by name
4. Energy summary (kWh/day)
5. Billing summary
0. Exit

Technical Concepts Applied

Arithmetic calculations

Input validation

Use of double for accurate cost computation

Formatted output using <iomanip>

Objective of Week 3

The objective of Week 3 is to simulate a real-world electricity billing system by combining energy consumption data with tariff-based cost calculations.