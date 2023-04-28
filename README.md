# Light_Following_Robot
Implements the interaction between sensors and hardware in a Light Following Robot. This code uses a planning, perception, and action code organization.

This code uses a preception, planning, action organization strategy in order to control the Light Following Robot. There are three sensors attached to the robot.
  1. A ultrasonic Sensor in order to monitor distance from the front of the Robot to any ostacles.
  2. A Combination of four photo diodes to monitor where light is coming from in front of the Robot
  3. A capacitive sensor to monitor for touch
  
Using the input from these three sensor the code interacts with 
  1. A sensor connected to the photodiodes.
  2. Two motors connected to the wheels of the Robot.
 
The code is set up to allow the robot to follow the light until it reaches it, then turning to the right to allow for wall following. The capacitive sensor toggles the 
speed of the robot, using pwm to monitor the speed.

The implementation of the code into the robot can be found at the video below.

https://youtu.be/r7_1FNwX_7s
