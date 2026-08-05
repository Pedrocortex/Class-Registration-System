# Student Attendance Registration System

A desktop application developed in Python to simplify student attendance registration through an intuitive graphical interface. The application stores attendance records in an Excel spreadsheet, making it easy to maintain and manage attendance history.

## Features
User-friendly graphical interface built with Tkinter
Student ID validation
AM/PM period selection
Attendance type selection (In-person or Online)
Session time selection
Automatic date registration
Automatic data storage in an Excel workbook
Color-coded spreadsheet formatting for improved readability
Automatic saving after each registration

## Built With:
Python 3
Tkinter
tkinter.messagebox
tkinter.ttk
OpenPyXL
os
datetime
openpyxl.styles (Alignment and PatternFill)

Project Structure:
.
├── Interface.py      # Main application interface
├── Insere.py         # Excel data handling
├── Pasta2.xlsx       # Attendance database
└── README.md
Installation

## Usage

Run the application:

python Interface.py

Then:

Select the session time.
Enter the student's ID.
Choose the attendance period of the day (AM or PM).
Select the attendance type (In-person or Online).
Click "Gravar Dados" (Save Data).
The record will be automatically saved in the Excel spreadsheet.
Excel Output

## Each attendance record includes:

Field	Description
Date	Registration date
Student ID	Student identification number
Period	AM or PM
Session Time	Selected session time
Attendance Type	In-person or Online

## The spreadsheet is automatically formatted to improve readability:

Light green for the Date column
Light blue for In-person attendance
Light yellow for Online attendance
Center-aligned cell content
Requirements
Python 3.10+
OpenPyXL

## Install dependencies:
Python 3.10 or later
pip install openpyxl
An existing Excel workbook 

# Demo

https://github.com/user-attachments/assets/bfa93484-972a-49a4-8537-fa0811ec4fd0


















