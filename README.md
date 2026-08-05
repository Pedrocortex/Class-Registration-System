
https://github.com/user-attachments/assets/ad7c6b39-eb9e-4d3b-94d9-fffeb5ff3bf0
## Student Attendance Registration System

#Description

This application was developed in Python to record student attendance through a graphical user interface built with Tkinter. The collected data is automatically stored in an Excel spreadsheet using the OpenPyXL library.

# The system records:

Attendance date
Student ID
Period (AM or PM)
Time slot
Attendance type (In-person or Online)

Each new record is automatically inserted into the next available row of the spreadsheet.

# Technologies Used
Python 3.x
Tkinter
OpenPyXL
Project Structure
Project/
│
├── Main.py              # Graphical User Interface
├── Insere.py            # Excel data writing module
├── Pasta2.xlsx          # Excel database
└── README.md

# Features
User-friendly graphical interface
Time selection through a dropdown menu
AM/PM period selection
Attendance type selection
Automatic registration of the current date
Automatic storage in an Excel spreadsheet
Automatic cell formatting
Color coding based on attendance type
Installation
Clone the Repository
git clone <repository-url>

or download the project files manually.

#  Install Dependencies
pip install openpyxl

Tkinter is included with most Python installations.

# Usage

Run the application with:

python Main.py

After launching the application:

Select the time slot.
Enter the student's ID.
Select the attendance period (AM or PM).
Select the attendance type.
Click "Gravar Dados" ("Save Data").

The information will be automatically appended to Pasta2.xlsx.

# Excel File Structure
Column	Description
A	Date
B	Student ID
C	Period
D	Time Slot
E	Attendance Type
Code Organization
Main.py


# Demo

https://github.com/user-attachments/assets/c8630da0-723a-4942-82cb-bdd50bb040da














