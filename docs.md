### **Docs Folder Structure**  

```plaintext
docs/
│
├── overview.md                  # Main documentation file
├── simulation_process.md        # Detailed simulation workflow
└── images/                      # Supporting images for documentation
    ├── workspace.png            # Screenshot of workspace setup
    ├── tool_config.png          # Screenshot of tool calibration
    ├── spray_process.png        # Simulation of spray painting in action
```

---

### **`overview.md`**

# **RoboDK Paint Station Simulation Documentation**

Welcome to the comprehensive documentation for the RoboDK Paint Station Simulation. This file explains the project overview, setup instructions, and workflow in detail.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Setup Instructions](#setup-instructions)
4. [Simulation Workflow](#simulation-workflow)
5. [Key Features](#key-features)
6. [Screenshots](#screenshots)

---

## **Introduction**

This project simulates a robotic paint station using the UR10e industrial manipulator in RoboDK. The simulation is designed to mimic a real-world spray-painting operation with high accuracy and includes Python scripting for realistic paint application.

---

## **Project Overview**

- **Objective**: Simulate spray-painting of an object using an industrial robot.
- **Platform**: RoboDK for simulation and Python for scripting.
- **Robot**: UR10e industrial serial manipulator.
- **Key Components**:
  - Reference frames for workspace alignment.
  - Tool calibration and selection.
  - Surface target programming.
  - Python-based macros for paint simulation.

---

## **Setup Instructions**

### **Prerequisites**
- **RoboDK**: Download and install from [robodk.com](https://robodk.com).
- **Python 3.x**: Install Python from [python.org](https://www.python.org).

### **Import RoboDK Files**
1. Open `paint_station.rdk` in RoboDK.
2. Verify the robot, tool, and object configurations.
3. Run the main program to simulate the painting process.

---

## **Simulation Workflow**

1. **Robot Selection**
   - Add the UR10e manipulator to the RoboDK workspace.
   - Configure its base frame to align with the workspace.

2. **Adding Reference Frames**
   - Create frames to ensure proper alignment of the robot, tool, and object.

3. **Object Selection**
   - Load the workpiece in `.stl` format and place it at the desired position.

4. **Tool Selection and TCP Setting**
   - Import the paint gun tool in `.tool` format.
   - Calibrate the Tool Center Point (TCP) to align it with the robot arm.

5. **Teaching Targets**
   - Define key surface points for painting.
   - Use RoboDK's teaching feature to program the robot's movement.

6. **Python Macro Integration**
   - Write the `SprayOn` Python macro for paint simulation.
   - Call the macro within the main program for realistic effects.

7. **Program Execution**
   - Combine all individual programs into a single main program.
   - Export the final program as a script for deployment.

---

## **Key Features**

- **Robot Configuration**:
  - UR10e manipulator with realistic motion paths.

- **Tool Integration**:
  - Paint gun with accurate scaling and calibration.

- **Realistic Simulation**:
  - Python scripting for enhanced realism in spray-painting.

- **Exported Scripts**:
  - Generate deployable code for robotic systems.

---

## **Screenshots**

### Workspace Setup
![image](https://github.com/user-attachments/assets/53b8efaf-df9b-45bd-8ded-acf30bde2f78)
 
*The robot, tool, and object aligned in the workspace.*

### Tool Calibration
![image](https://github.com/user-attachments/assets/84c71f2b-727e-4bd7-921a-e80114feb4b7)

*Calibration of the paint gun's Tool Center Point (TCP).*

### Spray Painting in Action

https://drive.google.com/file/d/1VnU5_aa4uJu5LRKRxqr3J2fQgMOZa4yg/view?usp=sharing

*The UR10e robot spraying paint on the surface of the workpiece.*

---

## **Additional Information**

For detailed simulation steps, refer to [`simulation_process.md`](simulation_process.md).  
If you have questions, feel free to open an issue on the GitHub repository.  

---

**Happy Simulating!** 🚀
---

## **References**

- **RoboDK Documentation**: [Getting Started with RoboDK](https://robodk.com/doc).
- **UR10e Datasheet**: [Universal Robots](https://www.universal-robots.com).

---
