# Python Work Hours Tracker

## Project Goal
This project is a Python-based time-tracking program designed to make recording work hours easier and more accurate. As a remote intern, I currently have to manually reconstruct my workday to log my hours. This program will simplify that process by allowing me to clock in and out while automatically recording my work sessions.

## MVP Scope
The first version of the program will include:
- **Clock In:** Record the current date and time when starting work.
- **Clock Out:** Record the current date and time when finishing work.
- **CSV Storage:** Save work sessions to a local CSV file.
- **Time Calculation:** Calculate the total duration of each work session and add it to a summary.
- **Verification:** Prevent users from clocking in or out multiple times incorrectly.

## Future Plans
After completing the MVP, I plan to add:
- **Stream Deck Integration:** Use a single button on my Elgato Stream Deck to clock in and out.
- **Google Calendar Integration:** Automatically track meetings as part of my work hours.
- **HR Platform Integration:** Eventually connect the program to my employer's HR platform to simplify submitting work hours, subject to authorization and security requirements.
- **Google Sheets Integration:** Synchronize recorded hours with a cloud spreadsheet for easier viewing and reporting.

## Tech Stack
- **Language:** Python
- **Libraries:** datetime, csv, pathlib
- **Data Storage:** Local CSV file
- **Development Environment:** Visual Studio Code
- **Version Control:** Git and GitHub
- **External APIs:** None required for the MVP

## Schedule
1. Create the GitHub repository with the main Python file and CSV data file.
2. Create a clock-in function that records the current date and time.
3. Create a clock-out function that records the ending date and time.
4. Create a function that calculates total hours worked and updates a summary.
5. Create a verification function to prevent duplicate clock-ins or clock-outs.
6. Test the program, fix bugs, and finalize documentation.
