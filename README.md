Type of Robot - Two Wheeled Self-Balancing Robot

Problem Statement: The outlined features of the robot mentioned in the competition are

1. ability to carry liquid load (of 1Kg)
2. traversing over a distance of 200m without spilling

Robot Assembly Design (Proposed Diagram):
The link below contains the CAD files of the self-balancing robot design, consisting of the full assembled body and the assembled leg in .STEP file format.
CAD files : shorturl.at/eoC58

Components to be used:
I.	List of Structure components:

Components
Dimensions
3 rectangular plate 
Length = 24cm  Width = 10cm 
4 Rod
Length = 26 cm
2 Wheels
Diameter = 10cm
Nut and Bolt
M3 x 20mm
Container
l=13 cm , b= 8 cm ,h= 20 cm


II.	List of Motion Components: like chain, sprockets, flaps etc.
Screw and Nuts
L-Shaped Brackets
III.	List of electronics components:
Raspberry Pi 3 (controller),
Li-Ion Battery (12V DC 30W)
A Switch,
2 DC Motors and motor adapters
Motor Driver
MPU 6050 sensor (gyroscope and accelerometer)
A Breadboard.

The methodology of Making Robot:

The two-wheeled self-balancing robot (TWSBR) is a standard robot with applications in various fields, including transportation and exploration. The physical characteristics of the robot are crucial to achieve optimal control. In practical applications It is frequently desirable to obtain optimality beyond simple stabilization.
The major objective of the self-balancing robot in the competition is the ability to carry liquid load (of 1Kg) over a distance of 200m without spilling. It is well known that placing open-lid containers over the top surface of such a robot are prone to slipping due to the smooth surface or unwanted interaction with the container, causing damage to the robot as well as to the 
surroundings. A possible solution to this challenge is to fix a removable container on the top surface as shown in the below diagram. While the container is not prone to the above problems. We plan to use this design of the robot in our proposition.
Modeling of the robot
For any robot to be functional, it requires the understanding of its dynamic and kinematic modeling. While dynamic modeling emphasizes on the control of the actuators or the driver motors in this case, kinematic modeling describes the kinematics of the robotic movements. 

Control System

Two wheeled self balancing robot uses a closed loop control system . It means that real time data is obtained from sensors (gyroscope in this case) as feedback to the controller which controls the motor and quickly balances the robot
We are going to use PID control for making a self balancing robot.
Where PID stands for
Proportional term, P = Error * Kp
Integral term, I = ( Error wrt time) * Ki
Differential term, D = (Error-prevError) * Kd
Where  Kp, Ki, Kd are the gain of P, I, D terms respectively.
Tuning of PID controller - For perfect balancing of the robot, we need to fine tune our Kp, Ki, Kd gains .

Application of proposed Robot in a societal context:

A two wheeled vehicle is safer for the inhabitant while simultaneously traveling  through the narrow city streets more easily than three wheels or four wheels drive.
Also due to lower mass configuration, it also increases its fuel efficiency and provides maneuverability . As it is battery driven so it does not contaminate the environment. 
Some of the applications include Segways which is a self balancing electric scooter  The current day short distance usage vehicles can be substituted by them. It is used as patrol officers by the police department,by tourists for local sightseeing and also as a platform for mobile robots.

Size of Robot proposed for Proof of Concept (Small Version):

a)	Length = 24cm
b)	Width = 10cm
c)	Height = 36cm

Size of Robot proposed for Proof of Concept (Actual Version):

a)	Length 24cm
b)	Width 10cm
c)	Height 36cm


			
