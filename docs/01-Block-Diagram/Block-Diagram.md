# Individual Block Diagram

## Overview
The purpose of this individual block diagram is to document the hardware architecture, electrical interfaces, and signal flow for the Servo Motor Subsystem of Team 102's Modular Spider Leg[cite: 2, 10]. Establishing this layout ensures clear communication with teammates regarding inter-board connections and helps organize the component selection process in preparation for creating the detailed hardware schematic[cite: 2]. 

Key system parameters include[cite: 17]:
* **Power Source & Levels:** The board is powered by an external 9V DC wall adapter, which is stepped down via a linear regulator (L7805CV) to a regulated 5V DC supply[cite: 14]. This 5V domain powers the servo motor, while the microcontroller's internal regulator supplies 3.3V for the logic domain[cite: 14].
* **Actuator & Sensors:** The primary actuator is a standard servo motor (e.g., TowerPro SG90) driven by a 5V PWM signal directly from the microcontroller[cite: 11, 14]. This specific subsystem operates purely as an actuation node and does not require local sensors[cite: 11].
* **Team Connections:** Operating as a "spoke" in our team's hub-and-spoke topology, this board connects to the main kinematics hub board using the class-standard 8-pin ribbon connector (Connector 1)[cite: 10, 11]. 
* **Signal Flow:** The central hub sends digital position commands via a serial connection on Pin 1 to the PIC18F57Q43 microcontroller's UART RX pin. The microcontroller translates this command and outputs a digital parallel PWM signal to drive the servo motor to the target angle

## Subsystem Block Diagram

![Akshan Bhelkar - Servo Motor Block Diagram](Akshan_Block_Diagram.png)

**Figure 1:** Hardware block diagram detailing the power distribution and hub connections for the Servo Motor Subsystem.
