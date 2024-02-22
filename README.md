# Calender_Using_C

This is a simple calendar generator written in C. The program generates a calendar for a given year, displaying each month's days with corresponding weekdays.

## How to Use
1. Run the program.
2. Enter the desired year for which you want to generate the calendar.
3. The program will display the calendar for the entire year, month by month, with days and weekdays properly aligned.

## Features
- Supports leap years (February will have 29 days for leap years).
- Generates a calendar for the entire year, displaying each month's days and weekdays.

## Running the Program
Ensure you have a C compiler installed on your system. You can compile and run the program using a C compiler like GCC.

```bash
gcc -o calendar.c
```

## Requirements
- C compiler (e.g., GCC)

## File Structure
- `calendar.c`: Contains the source code of the calendar generator.

## Note
- The program uses a function `firstweekday()` to calculate the weekday of the first day of the year.
- It dynamically adjusts the number of days in February for leap years.
- The output is formatted to display days and weekdays in a neat and organized manner.

Feel free to use this calendar generator to create calendars for any desired year and integrate it into your projects or applications!

---

**Author:** Anubhav Kumar Gupta
