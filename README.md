# Great-Urtuu
**Disclamer- This code was used for Abu-Robocon-2019 Asia Pacific Robotics Contest by the team Sardar Vallabhai National Institute of Technology, Surat.
	     This code is not to be shared on any public platform (open-source), please respect the privacy of this document.

This file consists of Arduino code for the Two layer system desined by the Team for a four-wheeled Omni-Drive robot.
Two-Layer - Upper Control and Lower Control 

1]Upper Control - 
It consists of an Arduino Mega(ATmega32). 
The major components included in Upper Control are:
-Basic Functions
-Communication (Easy_Transfer Libarary)
-Curve functins
-Drive control of the Robot
-Mpu6050
-PID Control 
-Shagai Control(for effective Throwing of Shagai)
-Line Following(LSA08)
-PS2 Controller
-Inverse Kinematic Model

2]Lower Control-
It consists of an Arduino Due(ARM Controller)
The major components included in Lower Control Are:
-PID Control
-Drive Initialisation 
-Encoder Interrupts

The code also consists a PS2 Communication block.
