# Project Statement – Carbon Footprint Calculator

## Problem Statement

Many individuals lack awareness about how their daily activities—such as electricity use, fuel consumption, and travel—contribute to carbon emissions. Calculating one’s personal carbon footprint can be confusing without the right tools, making it harder to understand environmental impact and take steps to reduce it. There is a need for a straightforward desktop application that quickly estimates a user's carbon footprint using a few simple inputs.

## Scope of the Project

This project is a basic desktop application built with Python and Tkinter. It estimates an individual's carbon footprint based on three inputs: electricity usage (kWh), fuel used (liters), and transport distance (km). The program multiplies each entry by a set emission factor, shows category-wise emissions, and calculates a total in kilograms of CO₂. It runs locally, is designed for one user at a time, and does not include advanced features like cloud storage, accounts, or country‑specific emission factors.

## Target Users

- Students seeking to learn about carbon footprints and coding.
- Individuals curious about their impact from electricity, fuel, and travel.
- Teachers and mentors wanting a simple demo for sustainability and Python programming.
- Beginners in Python interested in GUI application development.

## High-Level Features

- User-friendly graphical interface with Tkinter.
- Three input fields: electricity usage (kWh), fuel usage (liters), transport usage (km).
- Fixed emission factors for each category.
- Calculation of category-wise and total CO₂ emissions.
- Input validation (shows error message for non-numeric data).
- Reset button to clear all fields and results.
- Exit button with confirmation dialog.
- Debug print statements in the console for easier testing and troubleshooting.
