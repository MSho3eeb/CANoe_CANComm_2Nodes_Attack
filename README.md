# CANoe_CANComm_2Nodes_Attack
CANoe Project: Connecting Two Nodes on CAN Bus with Action Panels
CANoe

This repository contains a CANoe project aimed at simulating a simple automotive scenario. 
The project involves connecting two nodes on a CAN bus: an Engine node that sends speed and temperature data,
and a Dashboard node that receives and displays this data. The project also includes action panels to view and interact with the simulation.

**Table of Contents**
Introduction
Project Setup
Installation
Configuration
Nodes
Engine Node
Dashboard Node
Action Panels
Usage
Contributing
License
Introduction
The CANoe software tool from Vector is a powerful environment for simulating, 
analyzing, and testing CAN networks. This project demonstrates a basic use case of connecting two simulated nodes on a CAN bus: 
an Engine node and a Dashboard node. The Engine node sends speed and temperature data, which the Dashboard node receives and displays.

**Project Setup**
Installation
Download and install CANoe from the official Vector website: CANoe Downloads
Configuration
Clone this repository to your local machine.
Open CANoe and load the project file CANoe_Project.cfg.

**Nodes**
Engine Node
The Engine node is responsible for simulating the behavior of an automotive engine. It generates and sends simulated speed and temperature data over the CAN bus.

**Dashboard Node**
The Dashboard node simulates the car's dashboard. It receives the speed and temperature data from the Engine node and displays it on the dashboard interface.

**Action Panels**
This project includes action panels that provide a user interface to interact with the simulation:

**Engine Control Panel:** This panel allows you to control the speed and temperature parameters of the Engine node.
You can adjust the speed and temperature values and send them to the Engine node.

**Dashboard Display Panel:** This panel displays the received speed and temperature data on the Dashboard node's interface.

**Usage**
Open CANoe and load the project.
Start the simulation.
Use the Engine Control Panel action panel to adjust the speed and temperature of the Engine node.
Observe the changes in the Dashboard Display Panel as the Dashboard node receives and displays the updated data.
Contributing
Contributions to this project are welcome! If you find any issues or have ideas for improvements, feel free to create a pull request or open an issue.

To see the videos of the test and documents of the progress from this link
https://drive.google.com/drive/folders/1vk5tqJKDz1xRu5H6FWdCsTWf-J8Yr_BR?usp=drive_link
