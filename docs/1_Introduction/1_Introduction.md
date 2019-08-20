---
Title: Introduction
summary: 
authors:
    - Paulo Yamagata    
date: 2019/4/26
---

# Introduction

OptimumKinematics has been developed with the goal of providing users with a powerful kinematics tool that is both easy to use, and easy to integrate into your existing workflow. 

It can be used to rapidly simulate the kinematic properties of a suspension design, providing detailed output and visualization for a broad range of output channels.

OptimumKinematics builds upon the success of OptimumK, providing more scope for different suspensions, a greater selection of output channels and greater modularity between designs. The ability to animate and visualize motion, compare multiple suspension simulations back to back and import and output data in a standard format (for use in Microsoft® Excel or MATLAB®) all remain.

Major improvements for version two are:

* __New User Interface.__ The philosophy and workflow has stayed the same in OptimumKinematics as the previous release. However, the new interface uses controls that are available with the new version of the .NET® Framework (Version 4 and higher). This is now the same standard control interface used by other Windows® products.
    * An interface layout similar to the Windows® products should reduce the learning period of OptimumKinematics.
    * The Ribbon Bar Control for quick access to all of the functionalities of the software. Buttons are filtered depending on the active control.
    * A multiple document interface (MDI) allows for flexibility and customization of the layout of the application. The ability to make edits to multiple points and instantly see the comparison is now possible.
    * Adjust the size and display and location of the controls and window panes to better organize the working space and maximize performance.
* __New Project Framework.__ The project data is no longer saving in a single file. Each object (for instance: [Suspension](../2_Quick_Start/C_Design_Overview.html#Suspension), [Motion](../2_Quick_Start/C_Design_Overview.html#Motion) or [Analysis Results](../5_Detailed_Overview/D_Analysis.html#Analysis-Results)) is saved in a unique file. Each file has a specific extension and icon and will be easily recognized on your hard drive. The Project Tree reflects the directory that is created in your hard drive. This has multiple advantages:
    * The risk of corruption and losing all of the data belonging to one project is decreased. An object can be corrupted or missing without affecting the rest of the objects belonging to the project.
    * The loading and saving performance has been improved by more than 30%
    * The sharing of files is faster and easier with the new proprietary file. There is no need to use Excel as a tool to share files. 
    * Better organization of your [Suspension](../2_Quick_Start/C_Design_Overview#Suspension), [Motion](../2_Quick_Start/C_Design_Overview#Motion) and [Analysis Results](../5_Detailed_Overview/D_Analysis#Analysis-Results) objects with the introduction of a “Vehicle” level in the project tree.
* __New Design Tools.__ The input forms have been redesigned for faster design and modifications of your suspensions and motions.
    * Suspension points can be edited directly in the 3D visualization.
    * The static outputs of your suspension are calculated automatically and display in real-time.
    * Add/Remove/Modify motion points directly in the chart.
    * The possibility to interpolate your motion points to have a smooth curve.
* __New Analysis Tools.__ The tools that you know and use in OptimumK 1.1 have been redesigned and are now more powerful for faster and deeper analysis. The tools have been expanded to include:
    * Quick preview of the simulation result with a table or chart.
    * Display of the data is faster, thanks to the memory-mapping of the result file. This allows a faster reading of the simulation result data from the hard drive.
    * Table reports and chart data can be copied to the clipboard easily for use in other software such as Microsoft® Excel or MATLAB®.
    * Customizable graphs with more options for the title (font, color, etc.), axis (title, gridlines, primary and secondary, etc.), and legend.
    * More channels have been pre-calculated into the software to allow you to quickly analyze your simulation data from within the software. There is now no need for further post-software calculations.
    * Animated table, chart and 3D visualization for a complete review of your simulation. Animation is played on all tables, charts and 3D visualization in real-time.
