---
Title: Analysis Overview
summary: This section contains information about the Analysis features.
authors:
    - Pedro Brasil    
date: 2019/8/29
---

# Analysis Overview

After the simulation is complete, OptimumKinematics creates a result file. Then, it allows the display of a preview of the result file in the <span style="color:orange"> __Document Manager__ </span>, either in table or chart format. The selected channels for display in the preview chart (or table) are a global setting and so, are shared across all projects and results.

![Analysis Window](../img/2_Quick_Start/2_E_analysis_window.png)

Selecting results from the <span style="color:deepskyblue"> __Results Project Tree__ </span> brings up a quick preview of the data in the <span style="color:orange"> __Document Manager__ </span>. After selecting the <span style="color:mediumpurple"> __Reports Tree__ </span>, the user may add a new report. Three kinds of reports are available:

* [Chart](##Chart). Create a chart showing the selected data for the X and Y-axis.
* [Table](##Table). Create and compare tabular data between simulations.
* [View](##View). Create 3D Visualizations so you can spacially see what is happening in your simulation.
* [Worksheet](##Worksheet). Create an arrangement of Charts, Tables, and Views to assist in the analysis process.

## Chart

Report Charts allow the graphical plotting of two variables and their relationship to each other. One chart can accommodate multiple results, with the option to implement a secondary axis. Charts are fully customizable using the buttons on the <span style="color:green"> __Ribbon Control Bar__ </span> or by clicking inside the <span style="color:orange"> __Report Chart Area__ </span>. You can find further details in the [Detailed Overview](../3_Detailed_Overview/C_Simulation.md) section.

![Analysis Report Chart](../img/2_Quick_Start/2_E_analysis_report_chart.png)

## Table

<span style="color:orange"> __Report Tables__ </span> allow the tabular display of multiple channels across multiple runs next to each other. The user chooses channels for display through the <span style="color:lightslategrey"> __Report Input Data__ </span> pane, while the results selection happens at the <span style="color:red"> __Results Input Data__ </span> pane. Table data can be readily copied to the clipboard (Ctrl + C) for further analysis in external programs if required.

![Analysis Report Table](../img/2_Quick_Start/2_E_analysis_report_table.png)

## View

<span style="color:orange"> __Report Views__ </span> allow 3D visualization and animated playback of a vehicle through a simulation run. When the Forces Module is activated, the display of the force vectors can happen from the view window by selecting on the suspension link in the reports input data if the simulation correspondent to the selected result file had forces inputs. You may add new views from the <span style="color:green"> __Ribbon Control Bar__</span>.

The view <span style="color:orange"> __Document Manager__ </span>contains the following:

* <span style="color:red"> __Reports Input Data__ </span> contains a list of available simulation results for visualization. 
* In the <span style="color:orange"> __3D View__ </span> window the user can edit the suspension data points by double-clicking on the suspension points. Rotation, zooming, and panning (in all directions) are possible by either left, middle and right-clicking, and dragging the mouse. Additional visualization of the roll axis, pitch axis, and instant centers are available by enabling the display options in the [Options Menu](../2_Quick_Start/B_Options_Menu.md), located on the projects <span style="color:purple"> __Backstage__ </span>([Graphical User Interface](../2_Quick_Start/A_Launching_the_Application.md#Graphical-User-Interface), under __File__).
* __Comments__. Add comments to your design to help maintain organization.

![Analysis 3D View](../img/2_Quick_Start/2_E_analysis_3d_view.png)

## Worksheet

The <span style="color:orange"> __Worksheet__ </span> allows you the ability to view multiple [Charts](##Chart), [Tables](##Table), and [Views](##View) in the same viewing window. Arrange the sheets either __Horizontally__, __Vertically__ or __Tiled__ and watch them as the simulation progresses. 

![Worksheet Report](../img/2_Quick_Start/2_E_worksheet_report.png)