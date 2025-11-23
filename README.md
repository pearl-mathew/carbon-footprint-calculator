# Carbon Footprint Calculator – Tkinter Desktop App

A simple desktop application to estimate your personal carbon footprint based on electricity usage, fuel consumption, and transport distance. Developed in Python using Tkinter GUI as part of the CSE VITyarthi project by Pearl Mathew.

## Overview

This application provides an easy-to-use graphical interface to help you calculate your personal carbon emissions. Enter your electricity (kWh), fuel consumed (liters), and distance travelled (km), and the calculator instantly displays your carbon footprint in kilograms of CO₂.

## Features

- Intuitive Tkinter graphical user interface
- Input fields for electricity usage, fuel consumption, and transport distance
- Calculates emissions for each activity and total carbon footprint (kg CO₂)
- Input validation with clear error messages
- Reset and Exit buttons, including exit confirmation dialog
- Console debug messages for easier testing

## Technologies / Tools Used

- Python 3
- Tkinter (built-in Python GUI library)
- Any Python editor (VS Code, PyCharm, IDLE, etc.)
- Works on Windows, macOS, and Linux

## Steps to Install & Run

1. Make sure Python 3 is installed on your computer.
2. Download or clone this repository:
   - To clone:  
     ```
     git clone https://github.com/pearl-mathew/carbon-footprint-calculator.git
     cd carbon-footprint-calculator
- Or download as ZIP and extract the folder.
3. Run the program:
python carbon_calculator.py
4. The GUI window will open for use.

## How to Use

1. Enter your Electricity Usage (in kWh)
2. Enter your Fuel Usage (in liters)
3. Enter your Transport Usage (in km)
4. Click **Calculate** to display your carbon footprint (kg CO₂)
5. Use **Reset** to clear all input fields; **Exit** to close the app (with confirmation)

Empty inputs are treated as 0; invalid text will trigger an error dialog.

## Instructions for Testing

- Enter valid numbers and click Calculate: a total is displayed.
- Leave some fields empty and test: calculator works, treating blanks as zero.
- Enter letters or symbols and test: should show an error message and reset.
- Click Reset button: all fields and result are cleared.
- Click Exit: confirmation dialog appears before closing.

## Screenshots
![Python code part 1](screenshots/code1.jpg)
![Python code part 2](screenshots/code2.jpg)
![Python code part 3](screenshots/code3.jpg)
![Final result window](screenshots/final_result.jpg)


## Author

**Pearl Mathew**  
CSE VITyarthi Project
