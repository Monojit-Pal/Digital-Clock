Digital Clock

Description
This C program is a digital clock that continuously displays the current date and time. The clock can be set to either a 24-hour or 12-hour format based on the user's preference. It uses system time to update the display every second, providing an accurate and real-time digital clock.

Features:
1. Time Format Selection
Users can choose between a 24-hour format or a 12-hour format.
The program prompts the user to select the preferred time format at the start.
2. Real-Time Display
Continuously updates and displays the current date and time.
The date is displayed in the format: "Day of the week Month Day Year" (e.g., "Monday July 13 2024").
The time is displayed according to the selected format: "HH:MM
" for 24-hour or "HH:MM
AM/PM" for 12-hour.
3. Cross-Platform Compatibility
Clears the screen before each update to provide a clean display.
Compatible with both Windows and Unix-like systems.

Key Functions:
fill_date(char* buffer): Fills the buffer with the current date in the specified format.
fill_time(char* buffer, int format): Fills the buffer with the current time in the specified format (24-hour or 12-hour).
input_format(): Prompts the user to select the time format and returns the choice.
clear_screen(): Clears the console screen for both Windows and Unix-like systems to update the display.

Get Started
To use this digital clock, compile and run the provided source code. Follow the on-screen prompts to select the desired time format.

Compilation Instructions
Save the source code to a file named digital_clock.c.
Open a terminal or command prompt.
Navigate to the directory where the source code file is saved.
Compile the code using a C compiler, e.g., gcc digital_clock.c -o digital_clock.
Run the executable, e.g., ./digital_clock on Unix-like systems or digital_clock.exe on Windows.

Conclusion
This project demonstrates the use of system time functions and cross-platform compatibility in C programming. It showcases my ability to create a real-time application with user interaction and continuous updates. The digital clock can be extended with additional features such as alarm functionality or customization options for the display.
