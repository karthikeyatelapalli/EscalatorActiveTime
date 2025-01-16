# Escalator Active Time Calculator

This C program calculates the total time an escalator remains active based on the arrival times of individuals. It assumes a constant duration of 10 seconds for a single person to traverse the escalator. The program determines whether a person arrives while the escalator is still operating or after it has turned off. Based on this, it computes the total active duration of the escalator.

## Features
- Handles variable arrival times for individuals.
- Determines whether the escalator is still active when a new person arrives.
- Calculates the total active duration in seconds.

## Usage
1. Enter the number of people.
2. Enter the arrival times of individuals (in seconds).
3. View the total time the escalator remains active.

## How to Compile and Run
1. Save the program as `escalator_active_time.c`.
2. Compile the program:
   ```bash
   gcc escalator_active_time.c -o escalator_active_time
