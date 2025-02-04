
# ABB RobotStudio Machine Tending Simulation

## Overview
This project involves the development of an ABB robot layout for a Machine Tending operation using ABB RobotStudio software. The simulation utilizes the ABB IRB4600 industrial robot, demonstrating an automated workflow for picking, placing, and handling CNC machine operations.

## Robot and Components Used
- **Robot Model**: ABB IRB4600
  - **Payload Capacity**: 60 kg
  - **Reach**: 205 cm
- **Grippers Used**:
  - **Vacuum Cup**: Used for pick-and-place operations.
  - **Servo Fingers**: Used to open and close the CNC machine door.

## Process Workflow

### Pick and Place (Initial Step)
1. The robot picks up a cube placed on its right-hand side (RHS) using the vacuum cup.
2. It then approaches the CNC machine and places the cube inside.

### Door Closing Mechanism
1. The robot moves towards the CNC machine’s door handle.
2. Using the servo fingers, it grabs the handle and slides the door closed.
3. The robot then moves to a safe position.

### Door Opening and Part Retrieval
1. After processing, the robot moves near the closed door handle.
2. It grabs the handle with the servo fingers and slides it open.
3. The new cylindrical part inside the CNC machine is picked up using the vacuum cup.

### Placement of Processed Part
1. The cylindrical part is placed onto a table located on the left-hand side (LHS) of the robot.

### Returning to Home Position
1. The robot moves back to its designated home position, ready for the next operation cycle.

   ## Simulation
Watch the simulation in action on YouTube:  

[![Watch the Simulation](https://img.youtube.com/vi/GMUnlbIP_Ow/0.jpg)](https://youtu.be/GMUnlbIP_Ow)  



