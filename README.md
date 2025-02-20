# Emerging-Sys-Arch-Tech 
The goal of this class is to develop a project with thermostat control system using a Rasberry Pi with temperature sensor, LEDs, buttons, jumper wires, and a LCD Display. The system will operate as a state machine using Off, Heat, and Cool controlled by their respective buttons. The LCD displays the current time, temperature, and thermostat state, alternating every few seconds. The system sends status updates (state, current temperature, and setpoint) to a remote server via serial communication every 30 seconds. Developed as part of CS350 - Embedded Systems, this project demonstrates hardware-software integration, state machine design, real-time system threading, and serial communication. The code is written in Python, using libraries like gpiozero, adafruit_ahtx0, and adafruit_character_lcd. To use, connect the hardware as per the pin configuration, install dependencies, and run the program. Press CTRL-C to exit cleanly.


**What Did You Do Particularly Well?**

Hardware-Software Integration: Successfully interfaced with multiple hardware components (sensor, LEDs, buttons, LCD) using Python libraries like gpiozero and adafruit_character_lcd.

**Where Could You Improve?**

User Interface: Adding a web-based or mobile interface for remote control and monitoring would enhance usability.

**Tools and Resources Added to Your Support Network**

gpiozero for GPIO control.

adafruit_ahtx0 for temperature sensing.

adafruit_character_lcd for LCD display management.

**Transferable Skills**

Hardware-Software Integration: Experience with sensors, displays, and GPIO control is transferable to IoT and robotics projects.
Serial Communication: Knowledge of serial protocols is useful for interfacing with external devices and systems.
Debugging and Testing: Systematic debugging and testing practices are essential for all software and hardware development.

**Maintainability, Readability, and Adaptability**

Inline comments and a detailed README file ensure the code is understandable and accessible to others.
Clear state transitions and well-defined button actions ensure the code is readable and maintainable.
