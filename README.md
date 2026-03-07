Electrical Load Monitoring System
Author

Benedicta Dan Agbo

Project Overview

The Electrical Load Monitoring System is a C++ console-based application developed to monitor household electrical appliance energy consumption and estimate electricity costs.

The system allows users to register appliances, calculate total daily energy usage (kWh), and generate both daily and monthly billing reports based on a given electricity tariff.

This project demonstrates practical implementation of structured programming, file handling, data storage, and input validation in C++.

Features

Add new electrical appliances

Store appliance records in appliances.txt

Display all registered appliances

Calculate total energy consumption (kWh/day)

Generate daily billing report

Calculate estimated monthly cost (30 days)

Save billing results to billing_summary.txt

Input validation for accurate data entry

Program Formula Used

Daily Energy (kWh):

Energy = (Power in Watts × Hours per day) ÷ 1000

Daily Cost:

Cost = Energy × Tariff per kWh

Monthly Estimate (30 days):

Monthly Cost = Daily Cost × 30

Technologies Used

C++

STL (Vectors, Strings)

File Handling (fstream)

String manipulation

Structured programming

Git & GitHub for version control

Project File Structure
.gitignore
README.md
main.cpp
appliances.txt
billing_summary.txt
Sample Demo Data
appliances.txt
Radio|60|3
TV|50|3
AC|240|7
billing_summary.txt
=============== BILLING REPORT ================
No.  Name                kWh/day     Cost/day    
------------------------------------------------
1    Radio               0.180       3.60        
2    TV                  0.150       3.00        
3    AC                  1.680       33.60       
------------------------------------------------
Total Energy (per day): 2.010 kWh/day
Total Cost (per day):   40.20
Monthly Energy (30d):   60.300 kWh
Monthly Cost (30d):     1206.00
================================================


This project demonstrates understanding of:

Structs in C++

Vectors for dynamic storage

File reading and writing

Input validation techniques

Energy computation logic

Modular programming with functions

Basic billing automation

Git version control workflow

Conclusion

The Electrical Load Monitoring System provides a simple but effective solution for estimating electricity consumption and cost for household appliances. It reinforces core C++ programming principles and practical software development skills.