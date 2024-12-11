 Inefficient organization and management of household items can lead to inconvenience and
 wastage of resources. Traditional drawers lack intelligence and fail to provide timely reminders
 or monitor item quantities. There is a need for an innovative approach to household automation
 and organization that addresses these challenges. The aim of this project is to develop smart
 drawers equipped with reminder systems and weight sensing technologies to improve
 convenience, optimize inventory management, and enhance overall household automation. By
 integrating smart features into drawers, we seek to enhance user experience, reduce wastage,
 and streamline everyday tasks

  Hardware Components
 ● Arduino Board: An open-source microcontroller board based on the Atmel AVR
 microcontroller, used as the core processing unit for the Smart Drawer system.
 ● Force Sensor: A device that measures the force or weight applied to its surface,
 enabling the detection of weight changes within the drawer.
 ● Breadboard: A prototyping board that allows for easy connection and testing of
 electronic components without the need for soldering.
 ● Wires: Connecting elements used to establish electrical connections between different
 components in the system.
 ● Resister: A digital storage element used in electronic circuits to hold data or control
 signals.
 
 Software Components:
 ● Arduino Programming Language: Based on C/C++, the programming language used to
 develop the code running on the Arduino board. It enables the reading of sensor data,
 processing of information, and communication with other components.
 ● Node-RED: Aflow-based programming tool that provides a visual interface for
 connecting and controlling devices and services. In the Smart Drawer project,
 Node-RED serves as the central hub for receiving input from the Arduino board and
 displaying the corresponding status through a color-coded display.
 
 System Functionality:
 ● Weight Detection: The force sensor integrated into the drawer detects changes in weight
 as objects are added or removed.
 ● Real-time Status Indication: The system communicates the status of the drawer through
 color-coded signals displayed on the Node-RED interface. Green indicates a full
 drawer, blue signifies a brief delay, and red indicates an empty drawer.
 ● 10-Second Delay: After weight removal, the system introduces a 10-second delay
 before updating the status display. This delay allows users to observe the transitional
 state before receiving final feedback.

 
