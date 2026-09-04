# RFID Security System

A fail-safe smart access control system engineered to eliminate mechanical key vulnerabilities. Built around dual C8051F340 microcontrollers, this system utilizes MIFARE RFID authentication and a relay-driven 12V solenoid lock for rapid, secure entry. 

**System Architecture & Hardware**
* **Primary Control:** Dual C8051F340 MCUs programmed in Embedded C. (One as Admin, One for User)
* **Authentication Modules:** MIFARE RFID reader for primary access, integrated with a matrix keypad for manual fallback entry.
* **User Interface:** Real-time system status displayed across dual OLED and character LCD screens.
* **Actuation:** Relay-driven 12V solenoid lock mechanism.

**Impact & Recognition**
* Achieved <300ms unlock latency with 100% authentication accuracy.
* Secured 1st position in the Microcontroller and Applications university course.

**License**
Copyright (c) 2026 @yourusername. All Rights Reserved. No permission is granted to use, copy, modify, or distribute this code.
