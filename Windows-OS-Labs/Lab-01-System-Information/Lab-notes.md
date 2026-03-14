# Lab 01 – Exploring Processes, Threads, Handles, and the Windows Registry

## Objective
The objective of this lab was to explore Windows system components, including active processes, threads, handles, and the Windows Registry, using system monitoring and management tools.

This ab was performed on a **Windows 7 virtual macchine**, chosen because it is compatible with the Acer laptop (2009 model) Utilized for this course.

## Tools Used
Autoruns64 – To view and manage active processes and startup items  
Task Manager – To access running processes and system performance  
Resource Monitor – To inspect threads and resource usage  
Snipping Tool – To capture screenshots as evidence  

## Activities Performed
Investigated active processes in Windows using Autoruns64  
Examined threads and handles for selected processes  
Accessed Task Manager to locate and identify the web browser process  
Attempted to terminate specific processes using the Kill Process function  
Observed behavior of processes in relation to commands executed  

## Issues Encountered & Resolution

Issue 1:  
The `process.exe` tool refused to run when attempting to explore an active process.  

Resolution: 
Used Autoruns64 as an alternative to investigate active processes successfully.

Issue 2: 
The "Find Windows Process" tool was unavailable.  

Resolution:  
Pressed **Ctrl + Shift + Esc** to open Task Manager, which allowed access to the browser process.

Observation (not an issue):  
Noticed that the browser window process temporarily disappeared from the process list.  
*(This was for awareness only and did not affect lab completion.)*

Issue 3: 
Clicking **Kill Process** on `command.exe` did not terminate the command prompt window.  

Resolution:  
Selected **Kill Process** on `conhost.exe` instead, which successfully terminated the command prompt.

Issue 4: 
The **Threads** tab in the Properties window was unavailable.  

Resolution:  
Navigated to the **Performance** tab, then clicked **Resource Monitor** at the bottom to inspect threads and resource usage.

## Evidence
Screenshots demonstrating the steps and results of the lab are stored in the `screenshots` folder:
screenshots/ ├── process-list.png ├── browser-process.png ├── autoruns-view.png