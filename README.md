# Projectwork-KaToMi
This project is a group effort and is part of the embedded programming course organized by Opiframe. The goal was to create a prototype of a medication dispenser device, encompassing the conceptual level operation of the device's hardware, and particularly the code involved.

The main task of the medication dispenser is to dispense medications at desired intervals. When the target time is reached, the device rotates the magazine a certain amount to allow the medications to fall onto the tray. Once the medications are available, the device's IR sensor detects them and triggers an alarm.

Dispensing times, device, and client information are defined in a database. Another part of the project was the creation of a mobile application, which provides access to the database and sets the desired operation of the device. The purpose of the application was to enable the setting of times and provide log information about the device's use. Unfortunately, there wasn't enough time to implement all the desired functions in the mobile application. The mobile app allows adding and removing times to a local database, but it lacks a network connection to the dispenser.

The project served as a valuable lesson in how programming, especially close to the hardware, is done. We also gained practical experience in database management and the use of Git. Of course, the project also provided valuable experience in teamwork.

The concept of the project's dispensing device was implemented using a Raspberry Pi 4 computer, along with a 5V stepper motor and an FC-51 IR sensor. The Raspberry's code was written in Python. The mobile application code was developed in Java using Android Studio. The database was implemented with SQLite.

Project members:
Minttu Simula,
Kari Ervasti,
Toni Taikina-aho
