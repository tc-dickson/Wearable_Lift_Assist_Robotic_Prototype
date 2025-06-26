# Wearable Lift-Assist Robotic Prototype
An exoskeleton-like robotic prototype for Sandia National Laboratories

[![Demonstration Video](https://img.youtube.com/vi/ynV_N79aajg/0.jpg)](https://www.youtube.com/shorts/ynV_N79aajg)

## Overview
Out of a pool of 40+ engineers, I was selected to be a part of a team of 5 other individuals tasked with creating a prototype for Sandia National Laboratories to help prevent repetitive strain injuries in Department of Energy workers. As part of their duties, these workers were tasked with moving heavy lead blankets (very similar to tarps) as part of ongoing efforts to clean up decommissioned nuclear sites. The movements of lifting, carrying, and setting down these blankets over and over again was resulting in injury. We were asked to develop a devise that could assist these workers in their task by redirecting 50% of the load away from the body. 

After considering a wide range of alternatives we settled on a backpack-mounted, battery-operated device. Workers wearing the device would use a hooked handle to grasp onto the lead blanket whereupon sensors in the handle would communicate with the microcontroller to reel in or out a cable attached to the handle. My role was to create the electronics system, program the control system, and I even played a role in designing and manufacturing 3D printed parts for the device. In all, we delivered the successful prototype on-time, and under budget.

## Key Technologies

| Programming Language(s) | Hardware                                                                | Electronics                                                                 |
| ----------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| - C++ (Arduino)         | - 3D Printed Parts </br> - Reused Backpacking Frame </br> - Steel Cable | - Brushless DC Motor </br> - Repurposed Strain Gauges </br> - Drill Battery |

## Features / Capabilities
- PID motor controller dynamically adapts to user movement and load.
- 3D printed pulley housings keep the cable constrained to the desired path.
- Handle-mounted strain gauges detect changes in load.

## What I Learned
- I learned how to work in a team to go from concept to functioning prototype.
- I learned how to apply my varied skill set to play a role in completing many systems from mechanical, to electrical, to software.

## Files Included

| Folder/File | Description                                     |
| ----------- | ----------------------------------------------- |
| /media/     | Contains the final submission report for Sandia |
