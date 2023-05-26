# Theft Monitoring System

This is a Theft Monitoring System created on Tinkercad. It uses various components and sensors to detect and alert for potential theft scenarios.

## Components

The following components are used in this project:

- Arduino Uno: It serves as the main microcontroller unit and controls the entire system.
- PIR Sensor: Passive Infrared (PIR) sensor is used to detect motion within its range.
- Buzzer: The buzzer is used to generate an audible alarm when a theft is detected.
- LED: An LED is used to provide a visual indication of the system's status.

## Circuit Diagram

The circuit diagram for the Theft Monitoring System is as follows:

![image](https://github.com/arpitya/Theft-Monitoring-System/blob/a55f64957485c80caad6a5d5355210ee102f08d1/circuit_diagram.png)
## Features
The Theft Monitoring System includes the following features:

- <b> Motion Detection</b>: The system uses a motion sensor to detect any movement in the monitored area. When motion is detected, an alert is triggered.

- <b>Door/Window Sensors</b>: Magnetic door/window sensors are used to detect the opening and closing of doors or windows. If any of the sensors are triggered, an alert is generated.

- <b>Alarm System</b>: The system is equipped with an alarm that can be activated when a theft event is detected. The alarm alerts the surrounding area and serves as a deterrent to potential thieves.

- <b>Real-time Notifications</b>: When a theft event is detected, the system sends real-time notifications to the user. These notifications can be received via email, SMS, or a mobile app, depending on the chosen notification method.

- <b>Monitoring Dashboard</b>: A web-based monitoring dashboard is provided to visualize and monitor the status of the system. The dashboard displays the current status of the sensors, the history of theft events, and allows for system configuration.

## Usage

To use this system, follow these steps:

1. Set up the circuit as per the circuit diagram provided.
2. Copy the Arduino code (`theft_monitoring_system.txt`) to the Arduino Uno.
3. Power on the circuit.
4. The system will be in an armed state, waiting for any motion detection.
5. When motion is detected by the PIR sensor, the buzzer will sound and the LED will light up and LCD will show theft alert, indicating a potential theft.
6. To disarm the system, press the reset button on the Arduino Uno or power off the circuit.

## Arduino Code

The Arduino code for this project is available in the [theft_monitoring_system.txt](theft_monitoring_system.txt) file. You can download the code and copy it to your Arduino Uno using the Arduino IDE or any other compatible software.


## Author

- [Arpitya Kumar Singh ](https://github.com/arpitya)

## Acknowledgments

We would like to acknowledge the following resources and libraries that were used in developing this project:

- Tinkercad
- Arduino
