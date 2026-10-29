
# Smart Machine Condition Monitoring and Safety Alert System

## Assignment
DEX2013 - Programming for Engineering

## Description
This project uses Python to read machine readings from a CSV file.
It classifies machine conditions as Normal, Warning or Critical.
It also calculates summary statistics and creates two graphs.

## Required Libraries
- pandas
- matplotlib

## Installation
Run this command in the terminal:

python -m pip install pandas matplotlib

## How to Run
1. Place the Python file and CSV dataset in the same folder.
2. Open the folder in VS Code.
3. Run the program:

python studentID_python_monitoring.py

Replace studentID with your actual student ID.

## Expected Output
- CSV loading confirmation and number of readings
- Reading_ID and Status for each reading
- Mean, minimum and maximum of the five machine parameters
- Counts and percentages for Normal, Warning and Critical
- temperature_vs_time.png
- vibration_vs_time.png

## Testing
The program is tested using the ten classification test cases
provided in Section 8 of the assignment.

## Graphs
The temperature graph contains reference lines at 40°C and 50°C.
The vibration graph shows vibration changes over time.
