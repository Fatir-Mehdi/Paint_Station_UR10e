# Paint_Station_UR10e
This process organizes the RoboDK paint station simulation project into a modular GitHub repository with clear documentation, scripts, data, and testing files for better collaboration and reusability.

# **RoboDK Paint Station Simulation**  
### A modular project simulating an industrial painting process using the UR10e robot in RoboDK, with Python scripting for realistic spray painting.  

---

## **Overview**  
This project demonstrates the creation of a paint station simulation using RoboDK and the UR10e industrial serial manipulator. The goal is to simulate a spray-painting process where the robot applies paint to a 3D object with precision. The simulation includes setting up the workspace, configuring tools, teaching targets, and programming movements, culminating in realistic paint application using a Python macro.

---

## **Features**
- **Robot Selection**: Utilizes the UR10e industrial robot based on its payload, reach, and versatility.  
- **Workspace Setup**: Configures reference frames, tools, and objects for precise simulation.  
- **Realistic Tool Simulation**: Integrates a paint gun tool, scaled and calibrated using `.tool` and `.stl` files.  
- **Target Programming**: Teaches specific targets on surfaces for accurate movements.  
- **Python Scripting**: Leverages RoboDK's macro functionality to simulate paint application.  
- **Exported Code**: Generates ready-to-deploy robotic scripts for real-world applications.

---

## **Project Workflow**  
The entire simulation creation process includes the following steps:  

1. **Robot Selection**  
   - The **UR10e industrial serial manipulator** is selected based on its payload capacity, workspace coverage, and compatibility with RoboDK.  

2. **Adding Reference Frames**  
   - Establish workspace reference frames to ensure alignment between the robot, tool, and object.  

3. **Object Selection**  
   - Load the 3D model of the workpiece in `.stl` format and place it in the workspace.  

4. **Tool Selection & TCP Setting**  
   - Test tool configurations using 3D models in `.stl` format.  
   - Calibrate the Tool Center Point (TCP) for accurate spray positioning.  

5. **Paint Tool Integration**  
   - Import a realistic **paint gun tool** in `.tool` format, scale it, and integrate it into the setup.  

6. **Teaching Targets**  
   - Define key targets on the object surface and program the robot to move between them.  

7. **Main Program Creation**  
   - Combine individual programs into a comprehensive main program for the painting process.  

8. **SprayOn Macro**  
   - Write and integrate a Python macro (`SprayOn`) to simulate paint application with the tool.  

9. **Code Generation**  
   - Export the complete program as a script file from RoboDK for external use.  

---

## **License**
This project is licensed under the [MIT License](LICENSE).  

---

## **Screenshots**
![image](https://github.com/user-attachments/assets/545207f3-dc60-4c0d-8e29-6f9e7342655f)
Workspace Setup
*Workspace configured with UR10e, reference frames, and objects.*  

---

## **Acknowledgments**
- **RoboDK** for providing the simulation platform.  
- **Universal Robots (UR)** for the UR10e model.  

---

Feel free to use, enhance, and share this project. Happy coding and simulating! 🚀  
