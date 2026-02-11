# PRODUCT-RECOMMENDATION-SYSTEM

## Overview
A simple **Product Recommendation System** built in Python that generates product suggestions based on data and outputs reports in CSV and PDF formats.  


![Project Header](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python) 
![Database](https://img.shields.io/badge/Database-MySQL-orange?style=flat-square&logo=mysql)

A lightweight recommendation engine built in Python. This system processes product data from a MySQL database to generate smart suggestions, exporting the final results into professional CSV and PDF reports.

---

## 📂 Project Structure

```text
/Recom_proj/
├── proj.sql                   # MySQL database schema and initial data
├── project.py                 # Core application logic and processing
├── recommendation_report.csv  # Sample output for data analysis
├── recommendation_report.pdf  # Sample output for presentation
└── README.md                  # Project documentation

Email: khush.modi@outlook.com

🛠️ Prerequisites
Ensure you have Python 3.x and MySQL installed. You can install the necessary dependencies using the commands below:

1. System Dependencies (Linux Users)
If you are using the GUI features provided by Tkinter:

Bash
sudo apt-get install python3-tk
2. Python Libraries
Install the required libraries via pip:

Bash
pip install mysql-connector-python pandas matplotlib fpdf
🚀 Usage Guide
Step 1: Database Setup
Import the database schema into your MySQL server.

Log into your MySQL environment.

Run the commands inside proj.sql to create the tables and populate them with data.

Step 2: Running the Script
Execute the main Python file to process the recommendations:

Bash
python project.py
Step 3: View Results
Once the script completes, check the root folder for your reports:

CSV Report: Best for importing into Excel or other data tools.

PDF Report: A clean, readable document for stakeholders.

⚙️ Features
Database Integration: Seamless connection with MySQL.

Data Analysis: Uses Pandas for efficient data manipulation.

Automated Reporting: Generates dual-format outputs automatically.

Visualizations: (Optional) Support for Matplotlib plotting.
