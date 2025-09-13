Irfan Smart Door Lock

Overview

This project is a smart door lock using ESP32 WROOM 38-pin with:

L9110S motor driver (100ms pulses, dual plastic gear)

4 LEDs (Forward, Backward, Charging/Battery, Sleep)

Buzzer (Tik-tik-tik alert)

TFT Display (Bina SD card, shows status & battery)

Password management + OTP-ready

Bluetooth + Wi-Fi dual connectivity

Modular & expandable code

One-time upload ready for phone / Droid app


Wiring Diagram

See wiring/WiringDiagram.png for connections.

Features

1. Motor Forward/Backward (Lock/Unlock)


2. LEDs feedback


3. Buzzer alerts


4. TFT status display


5. Password verification & changeable via app


6. OTP-ready for future app integration


7. Bluetooth + Wi-Fi connectivity


8. Modular & expandable for future add-ons



Upload Instructions

1. Connect ESP32 to your phone via OTG cable.


2. Open your ArduinoDroid / Droid IDE app.


3. Load SmartDoorLock.ino.


4. Select ESP32 WROOM 38-pin board.


5. Upload the code.


6. Connect motor, LEDs, buzzer, TFT as per wiring diagram.


7. Power ESP32 with 5V via DC-DC converter, Motor with 7.4V battery.



Usage

Use Droid App or Bluetooth Serial to send commands:

Lock: LOCK:<password>

Unlock: UNLOCK:<password>

Change Password: PASS:<newpassword>


TFT display shows real-time status messages.

Sleep LED blinks when system is active.

Buzzer alerts for actions and wrong passwords.


Future Expansion

Wi-Fi web server commands

Battery monitoring with charging LED

Extra sensors or LEDs

USB LCD integration

OTP integration via mobile app


