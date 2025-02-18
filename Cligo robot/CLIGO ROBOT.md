USER GUIDE STEPS TO USE THE CLIGO ROBOT 

Link for product :- https://robu.in/product/cligo-wireless-bluetooth-controlled-gripper-robot-car-kit-for-kids/

Link for the Driver :- https://sparks.gogo.co.nz/ch340.html

1.  Download attachments from the provided link :- https://robu.in/product/cligo-wireless-bluetooth-controlled-gripper-robot-car-kit-for-kids/

2.  Download the Driver  from the Driver link provided  [Windows CH340 Driver](https://sparks.gogo.co.nz/assets/_site_/downloads/CH34x_Install_Windows_v3_4.zip)
3.  Download the Arduino IDE :- https://www.arduino.cc/en/software
4.  Verify and Upload Cligo.ino  in the Uno
5.  Use any  Bluetooth app or serial port terminal to control Cligo robot
6.  Here are the basic commands you can use to control your robot via Bluetooth:

	1. **"3" - Pick**
	    
	    - Moves the servo to 0 degrees (Pick an object).
	2. **"1" - Place**
	    
	    - Moves the servo to 60 degrees (Place an object).
	3. **"2" - Move Forward**
	    
	    - The robot moves forward.
	4. **"8" - Move Backward**
	    
	    - The robot moves backward.
	5. **"5" - Stop**
	    
	    - The robot stops moving.
	6. **"4" - Turn Left**
	    
	    - The robot turns left.
	7. **"6" - Turn Right**
	    
	    - The robot turns right.
	8. **"Sharp Left"** (Not in the main loop, but defined)
	    
	    - The robot makes a sharper left turn.
	9. **"Sharp Right"** (Not in the main loop, but defined)
	    
	    - The robot makes a sharper right turn.