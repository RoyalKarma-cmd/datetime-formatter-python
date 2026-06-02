# Datetime Formatter Python

## Project Overview

Datetime Formatter is a Python project that demonstrates how to format and display dates and times using Python's built-in `datetime` module.

The project converts raw date-time information into user-friendly formats, making it easier to read and understand.

This project is useful for learning how real-world applications display dates, times, days, and months.

---

## Features

* Display Current Date
* Display Current Time
* Display Current Day Name
* Display Current Month Name
* Format Date Using `strftime()`
* Format Time Using `strftime()`

---

## Technologies Used

* Python
* Datetime Module

---

## Concepts Used

### Datetime Module

```python
from datetime import datetime
```

### Current Date and Time

```python
datetime.now()
```

### Date Formatting

```python
strftime()
```

---

## Format Codes Used

| Code | Meaning               | Example   |
| ---- | --------------------- | --------- |
| `%d` | Day                   | 03        |
| `%m` | Month Number          | 06        |
| `%Y` | Full Year             | 2026      |
| `%H` | Hour (24-hour format) | 15        |
| `%M` | Minutes               | 45        |
| `%S` | Seconds               | 20        |
| `%A` | Full Day Name         | Wednesday |
| `%B` | Full Month Name       | June      |

---

## Sample Output

```text
Current Date:
03-06-2026

Current Time:
15:45:20

Day:
Wednesday

Month:
June
```

---

## Learning Outcomes

Through this project, I learned:

* How to use Python's `datetime` module
* How to get the current date and time
* How to format dates using `strftime()`
* How to display day and month names
* How date formatting is used in real-world applications

---

## Real-World Applications

* Digital Clocks
* Attendance Systems
* Expense Trackers
* Banking Applications
* Employee Management Systems
* Event Scheduling Systems
* Data Science Time-Series Analysis

---

## Future Improvements

* Display Current Year
* Display Current Weekday Number
* Add Multiple Date Formats
* Create a Live Digital Clock
* Build a GUI Version using Tkinter

---

## Repository Structure

```text
datetime-formatter-python/
│
├── Date-Time-Formatter.ipynb
├── README.md
└── screenshots/
```
