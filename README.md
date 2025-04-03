This script analyzes revenue and loss data from DBT.csv based on user-inputted year and quarter. It follows these steps:

Load Data – Reads the CSV file and ensures correct column names.

User Input – Prompts for a year (2003-2005) and quarter (1-4).

Filter Data – Extracts revenue and loss for the selected period.

Identify Previous Period – Determines the previous quarter (or Q4 of the previous year if Q1 is selected).

Compute Metrics – Calculates total revenue, loss, and their changes compared to the previous period.

Display Results – Prints the revenue, loss, and year-over-year (YoY) changes.

Handle Errors – Catches invalid inputs and displays appropriate messages
