# Mobiux_developer_assignment
A C++ program for analyzing ice cream parlour sales data, including monthly sales totals, popular items, revenue generation, and order statistics.

## Table of Contents
1. [Installation](#installation)
2. [Features](#features)
3. [File Structure](#file-structure)
4. [Dependencies](#dependecies)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
2. Navigate to the project directory:
   ````bash
   cd your-project
3. Compile the code (if applicable):
   ````bash
   g++ one.cpp -o sales_analysis
4. Run the program
   ````bash
   ./sales_analysis

## Features
1. **Total Sales Calculation**: Outputs the total revenue generated across all data.
2. **Monthly Sales Totals**: Shows total sales per month.
3. **Most Popular Items**: Finds the most frequently sold item for each month.
4. **Top Revenue-Generating Items**: Identifies the item with the highest revenue each month.
5. **Order Statistics**: Provides minimum, maximum, and average order quantities for the most popular items each month.

## Dependencies
This program uses the following C++ libraries:
   ##<iostream>##: For standard input and output.
   ##<fstream>: For file reading.
   ##<sstream>: To parse CSV data.
   <vector>: To store sales data records.
   <map>: To track monthly sales, popular items, and revenue.
   <iomanip>: For setting the precision of floating-point output.
   <limits>: To set min/max limits for order statistics.
