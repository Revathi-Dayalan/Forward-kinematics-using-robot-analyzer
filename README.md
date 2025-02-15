Forward-kinematics-using-robo-analyzer
AIM:
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles

COMPONENTS REQUIRED:
1.Robo analyzer software

THEORY:
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters With DH Parameters, solving for the Forward Kinematics is easy. only need to take four parameters for each joint i: θifor the joint angle, αi for the link twist, difor the link offset, and ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:

![image](https://github.com/user-attachments/assets/70e3cec9-f43a-4b2e-b323-656dbca4768d)

![image](https://github.com/user-attachments/assets/67f9a5db-dba4-4cab-9866-2a98c43a0a39)


PROCEDURE:
1.open the roboanalyzer software. 2.select the robot and its degrees of freedom. 3.change the values with the link lenght wherever necessary. 4.simulate the model for forward kinematics. 5.plot the graph between the link and the joints. 6.update the DH parameters of the link configuration and end effector configuration.

![image](https://github.com/user-attachments/assets/f88ff6a9-575d-45ac-b2b8-068f3d383639)


SIMULATION
4 DOF:
![image](https://github.com/user-attachments/assets/456c4fa7-4117-4c8e-93a7-47cc727b5e5e)


6 DOF:
![image](https://github.com/user-attachments/assets/4b8c58e1-b35e-48fb-ba39-77290a1528c2)


PLOT
4 DOF:
![image](https://github.com/user-attachments/assets/da68ffef-4b9f-434b-9f77-dd51724f18fa)


6 DOF:
![image](https://github.com/user-attachments/assets/22d9ea1e-4f4a-40e9-bb65-36e6786a6738)


RESULTS :
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.



 














### RESULTS :  
