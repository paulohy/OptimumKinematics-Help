---
Title: Introduction
summary: 
authors:
    - Paulo Yamagata
    - Pedro Brasil   
date: 2019/4/26
---

# Introduction

OptimumKinematics is a powerful kinematics tool that is both easy to use and to integrate into your existing workflow. It can be used to rapidly simulate the kinematic properties of suspension design, providing detailed output and visualization for a broad range of output channels.

OptimumKinematics builds upon the success of OptimumK, providing more scope for different suspensions, a more extensive selection of output channels, and greater modularity between designs. The ability to animate and visualize motion, compare multiple suspension simulations back to back, and import output data in a standard format (for use in Microsoft® Excel or MATLAB®) all remain.

Significant improvements for version two are:

* __New User Interface.__ The philosophy and workflow have stayed the same in OptimumKinematics as the previous release. However, the new interface uses controls that are available with the new version of the .NET® Framework (Version 4 and higher). This new version is now the same standard control interface used by other Windows® products. Some remarks on the new User Interface are:
    * An interface layout similar to the Windows® products should reduce the learning period of OptimumKinematics.
    * The Ribbon Bar Control allows quick access to all the functionalities of the software. Buttons are filtered depending on the active control.
    * A multiple document interface (MDI) allows for flexibility and customization of the layout of the application. The ability to make edits to multiple points and instantly see the comparison is now possible.
    * Adjust the size and display and location of the controls and window panes to improve the working space organization and maximize performance.
* __New Project Framework.__ The project data is no longer saving in a single file. The software uses a unique file type to save each object (for instance; [Suspension](../2_Quick_Start/C_Design_Overview.md#Suspension), [Motion](../2_Quick_Start/C_Design_Overview.md#Motion), [Force](../2_Quick_Start/C_Design_Overview.md#Force), or [Analysis Results](../3_Detailed_Overview/D_Analysis.md#Analysis-Results)). Each file has a specific extension and icon for easy recognition on your hard drive. The <span style="color:deepskyblue"> __Project Tree__ </span> reflects the directory created on your hard drive. This reflection has multiple advantages:
    * Decreases the risk of corruption and losing all the data belonging to one project. An object can be corrupted or missing without affecting the rest of the objects belonging to the project.
    * Improves the loading and saving performance by more than 30%.
    * The sharing of files is faster and easier with the new proprietary file. There is no need to use Excel as a tool to share files. 
    * Better organization of your [Suspension](../2_Quick_Start/C_Design_Overview.md#Suspension), [Motion](../2_Quick_Start/C_Design_Overview.md#Motion), [Force](../2_Quick_Start/C_Design_Overview.md#Force), and [Analysis Results](../3_Detailed_Overview/D_Analysis.md#Analysis-Results) objects with the introduction of a “Vehicle” level in the project tree.
* __New Design Tools.__ The redesigned input forms allow faster design and modifications of your suspensions and motions.
    * Suspension points can be edited directly in the 3D visualization.
    * The software calculates and displays static outputs of your suspension automatically and in real-time.
    * Add/Remove/Modify the motion applied to a vehicle using the motion chart.
    * The possibility to interpolate your motion points to have a smooth curve.
* __Calculate Suspension Pickup Point Forces.__ New to OptimumKinematics is the ability to calculate the forces in the suspension pickup points based on an external force applied at the contact patch.  This ability is a first in an OptimumG software and now brings the next step of vehicle design and analysis to you with the same ease of generation you have come to know.  Available with the force simulation:
    * Vector preview of the force magnitude applied at the contact patch and the force components applied at each pickup point.
    * Export magnitude forces to a full table or as a peak force value.
    * Ability to apply forces on the vehicle at either the contact patch or at the wheel center.
    * Add/Remove/Modify force instances by directly applying an instance in the forces plots.
    * Ability to import force data from a .csv file and apply forces generated from a wheel force transducer or a full vehicle simulation, allowing for more accurate load cases.
* __New Analysis Tools.__ The tools that you know and use in OptimumK 1.1 have been redesigned and are now more powerful for faster and more in-depth analysis. The tools have been expanded to include:
    * Quick preview of the simulation result with a table or chart.
    * Memory-mapping of the result file allows for faster display of the data and reading of the simulation data from the hard drive.
    * Table reports and chart data can be copied to the clipboard easily for use in other software such as Microsoft® Excel or MATLAB®.
    * Customizable graphs have more options for the title (font, color, and such), axis (title, gridlines, primary and secondary, and such), and legend.
    * More channels have been pre-calculated into the software so you can quickly analyze your simulation data from within the software. There is now no need for further post-software calculations.
    * Animated table, chart, and 3D visualization for a complete review of your simulation. The animations play on all tables, charts, and 3D visualization in real-time.
