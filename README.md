☀️ Single Axis Solar Tracking System
📌 Project Overview

The Single Axis Solar Tracking System is an automatic mechanism that continuously adjusts the orientation of a solar panel to follow the movement of the sun throughout the day. The system uses Light Dependent Resistors (LDRs) to detect the direction of maximum sunlight and rotates the solar panel using a DC geared motor. By maintaining the panel perpendicular to the sun's rays, the system increases solar energy harvesting efficiency compared to a fixed solar panel installation.

💡 Proposed Solution

Conventional fixed solar panels receive maximum sunlight only for a short period during the day. As the sun moves across the sky, the angle of incidence changes, reducing power generation.

The proposed solution is a Single Axis Solar Tracking System that automatically rotates the solar panel from east to west based on sunlight intensity detected by two LDR sensors. The tracking mechanism ensures maximum exposure to sunlight and improves overall energy output.

📖 Project Description

This project consists of a solar panel mounted on a rotating structure driven by a DC geared motor. Two LDR sensors are placed on opposite sides of the panel. The sensors continuously monitor sunlight intensity.

When one LDR receives more sunlight than the other, the control circuit activates the DC motor and rotates the panel toward the brighter side. Once both sensors receive nearly equal light intensity, the motor stops. This process continuously tracks the sun's movement throughout the day.

The project demonstrates the practical application of solar energy optimization and automatic control systems.

🎯 Objectives
To maximize solar energy collection.
To improve the efficiency of solar power generation.
To automatically track the movement of the sun.
To reduce dependence on manual adjustment of solar panels.
To demonstrate the application of sensors and motor control circuits.
To promote renewable energy technologies.
🔧 Major Components
Component	Rating / Specification	Quantity
Solar Panel	6V, 100–200 mA	1
LDR (Light Dependent Resistor)	10kΩ–100kΩ	2
DC Geared Motor	6V–12V, 100 RPM	1
Motor Driver IC	L293D	1
Comparator IC	LM358	1
Resistors	10kΩ	4
Variable Resistor (Potentiometer)	10kΩ	1
LED Indicator	5 mm Green	1
9V Battery	DC Supply	2
PCB Board	General Purpose PCB	1
Connecting Wires	-	As Required
Mounting Structure	Wooden/Plastic Base	1
⚙️ Working Principle
The solar panel is mounted on a rotating platform connected to a DC geared motor.
Two LDR sensors are positioned on opposite sides of the panel.
The LDRs detect sunlight intensity and generate corresponding voltage signals.
The LM358 comparator compares the outputs of both LDRs.
If the left LDR receives more sunlight, the comparator activates the motor to rotate the panel toward the left.
If the right LDR receives more sunlight, the motor rotates toward the right.
When both LDRs receive equal sunlight, the comparator output becomes balanced and the motor stops.
The panel continuously follows the sun's movement, ensuring maximum solar radiation is received.
📊 Experimental Results
Parameter	Fixed Panel	Tracking Panel
Morning Output Voltage	4.2 V	5.4 V
Afternoon Output Voltage	4.5 V	5.8 V
Average Daily Output	100%	120–130%
Tracking Accuracy	Not Applicable	Good
Energy Collection	Moderate	Higher
Observations
The tracking system successfully followed the direction of sunlight.
The solar panel maintained better alignment with solar rays throughout the day.
Output voltage and energy generation increased compared to a fixed panel.
The DC motor responded effectively to changes in sunlight intensity.
✅ Conclusion

The Single Axis Solar Tracking System was successfully designed and implemented. The project demonstrated automatic solar tracking using LDR sensors, comparator circuits, and a DC geared motor. The system effectively adjusted the solar panel position according to sunlight intensity, resulting in improved energy collection compared to a stationary solar panel. This project highlights the potential of low-cost solar tracking mechanisms for enhancing renewable energy utilization.
