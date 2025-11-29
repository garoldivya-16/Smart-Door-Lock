# 🔐 Smart Door Lock Using Arduino, Keypad, LCD & Servo

This project implements a digital smart door lock system using an Arduino Uno, 4×4 keypad, 16×2 LCD, and a servo motor.
The user enters a password using the keypad, and if the password is correct, the servo rotates to unlock the door.

# Features

- 4×4 keypad input for password

- LCD display for instructions and status

- Servo motor acts as door lock

- Change password easily in code

- Error message for wrong password

- Low-cost and beginner friendly

# Components Required
Component	Quantity

- Arduino Uno	  -    1

- 4×4 Keypad	  -    1

- 16×2 LCD	    -    1

- Potentiometer (250kΩ) -	1

- Servo Motor    - 	1

- Breadboard	   -   1

- Jumper Wires	 -  As required

# How It Works

1. User enters a password on the keypad.

2. LCD displays the typed characters.

3. Arduino compares input with preset password.

4. If correct →
 ✔ Servo rotates to unlock
 ✔ LCD shows “Access Granted”

5. If wrong →
 ❌ LCD shows “Wrong Password”

6. To Lock again → Press " * "

 # What I Have Learned

1. Working of a Smart Door Lock System:

- Understood how an electronic door lock works using keypad input and a servo motor.
- Learned how to lock/unlock the door using a password system.

2. Using a Keypad with Arduino:

- Learned how to connect a 4×4 matrix keypad to Arduino.
- Understood how the rows and columns work to detect key presses.
- Used the Keypad.h library to read characters from the keypad.

3. Interfacing an LCD Display

- Learned how to connect a 16×2 LCD to show messages like:
  
    “Enter Password” ,
 “Access Granted” ,
 “Access Denied”
- Used the LiquidCrystal.h library for printing text.
 
4. Ardino Programming Concepts
   
- Using: Variables, if else conditions, Looping (for,while), Functions
   Learned to compare entered password with the stored password.

5. Real-life Application Awareness
   
 - Understood how smart locks are used in:
 Homes
 Offices
 Lockers

6. Servo Motor Control
  
7. Wiring and Circuit Skills

# Tinkercad Link
https://www.tinkercad.com/things/7H97LHh0Tzx-divyas-smart-door-lock
