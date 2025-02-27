Python Countdown Timer
Description
This script is a simple countdown timer that takes a user-specified duration (in seconds) and counts down to zero. It displays the remaining time in the format HH:MM:SS and updates every second. Once the countdown is complete, it prints a message indicating that time is up.

Features
Accepts user input for the timer duration in seconds.
Converts the total seconds into hours, minutes, and seconds for better readability.
Uses a for loop to decrement the time and display updates in real-time.
Implements time.sleep(1) to ensure accurate second-by-second countdown.

Requirements
Python 3.x
time module (built-in)

How It Works
The user inputs the desired duration in seconds.
The script calculates the hours, minutes, and seconds from the total time.
A loop runs, printing the time in HH:MM:SS format, updating every second.
When the timer reaches zero, the script prints a final message.

Usage
Run the script in a Python environment.
Enter a valid integer representing the countdown duration.
Wait for the countdown to complete.

Notes
Ensure that the input is a valid integer to prevent errors.
The timer is displayed in a fixed-width format (HH:MM:SS) for clarity.
The script sleeps for 1 second between updates, ensuring accurate timing.
