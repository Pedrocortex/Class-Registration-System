# Class Registration System

A lightweight Python desktop application for recording class attendance and storing lesson information in an Excel spreadsheet.

The application provides a simple graphical interface that allows instructors to quickly register classes by entering the student ID, class schedule, period, and attendance type.

## Features

- Desktop interface built with Tkinter
- Register student ID
- Select class schedule (1–12)
- Choose class period:
  - AM
  - PM
- Select attendance type:
  - In-person
  - Online
- Automatically records the current date
- Stores all records in an Excel workbook
- Color-coded attendance types for easier visualization

## Technologies

- Python 3
- Tkinter
- OpenPyXL
- Microsoft Excel (.xlsx)

## Project Structure

```
.
├── Interface.py        # Graphical User Interface
├── Insere.py           # Excel data management
├── Pasta2.xlsx         # Data storage
├── README.md
└── requirements.txt
```

## Requirements

- Python 3.10 or higher

## Dependencies

Install the required package:

```bash
pip install openpyxl
```

Or install all dependencies using:

```bash
pip install -r requirements.txt
```

### requirements.txt

```text
openpyxl>=3.1.0
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/class-registration-system.git
```

Navigate to the project directory:

```bash
cd class-registration-system
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python Interface.py
```

Fill in the required information:

- Student ID
- Class Schedule
- Period (AM or PM)
- Attendance Type (In-person or Online)

Click **Save Data** to store the record in the Excel spreadsheet.

## Data Organization

Each registered class contains:

- Date
- Student ID
- Period
- Class Schedule
- Attendance Type

The data structure allows easy filtering, reporting, and analysis using Microsoft Excel or business intelligence tools.

## Future Improvements

- Student search
- Automatic duplicate detection
- Attendance statistics
- Dashboard with charts
- CSV export

# Demo

https://github.com/user-attachments/assets/bfa93484-972a-49a4-8537-fa0811ec4fd0


## License

This project is licensed under the MIT License.




















