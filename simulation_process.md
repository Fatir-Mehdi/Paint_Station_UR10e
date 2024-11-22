
---

### **`simulation_process.md`**

# **Simulation Process Details**

This file explains the detailed step-by-step process for creating the paint station simulation in RoboDK.

---

## **Step-by-Step Guide**

### **1. Workspace Setup**
1. Add the UR10e robot from the RoboDK library.
2. Define reference frames for the robot base, tool, and object.
3. Import the workpiece model (`ObjectModel.stl`) into the workspace.

### **2. Tool Integration**
1. Import the paint gun model in `.tool` format.
2. Calibrate the TCP to align with the robot flange.
3. Test the tool's movement using RoboDK's tool visualization feature.

### **3. Teaching Targets**
1. Use RoboDK's "Teach Target" option to define surface points on the object.
2. Create a program to move between these targets smoothly.

### **4. Python Macro Integration**
1. Write the `SprayOn` macro in Python to simulate paint spraying.
2. Test the macro by running it on a simple motion program.

### **5. Combining Programs**
1. Integrate all individual programs into a main program.
2. Add the macro call within the main program.

### **6. Simulation Execution**
1. Run the main program in RoboDK to visualize the painting process.
2. Export the final program as a script for real-world deployment.

---

## **References**

- **RoboDK Documentation**: [Getting Started with RoboDK](https://robodk.com/doc).
- **UR10e Datasheet**: [Universal Robots](https://www.universal-robots.com).

---
