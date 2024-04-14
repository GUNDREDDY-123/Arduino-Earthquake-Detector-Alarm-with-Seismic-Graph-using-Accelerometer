# Arduino-Earthquake-Detector-Alarm-with-Seismic-Graph-using-Accelerometer
Arduino Earthquake Detector Alarm with Seismic Graph
Overview
This project utilizes the ADXL335 3-axis accelerometer as a sensor to detect tilting, trembling, or shaking movements indicative of an earthquake. An Arduino board is interfaced with the accelerometer and an LCD display to create an Arduino Earthquake Detector Alarm with a Seismic Graph. The system triggers a buzzer or LED alarm when the shaking threshold exceeds predefined limits, providing a visual and audible alert.

Components Required
Arduino Uno Board
ADXL335 Accelerometer
16x2 LCD Display
Buzzer
LED
Circuit Diagram & Connections

Working Explanation
Arduino Code for Earthquake Detection
The Arduino code reads the X, Y, and Z acceleration values from the ADXL335 accelerometer.
It compares the changes in acceleration with predefined thresholds (maxVal and minVal).
When the acceleration values exceed these thresholds, indicating earthquake-like movements, the buzzer and LED are activated.
Processing IDE Code for Seismic Graph
The Processing IDE code receives the X, Y, and Z acceleration values from the Arduino board.
It plots these values in real-time, creating a seismic graph on the computer.
By observing the graph, users can visualize the intensity and direction of the detected vibrations.
Steps to Use
Setup Arduino Code

Connect the Arduino Uno board to the ADXL335 accelerometer, LCD display, buzzer, and LED as per the circuit diagram.
Upload the provided Arduino code to the Arduino board using the Arduino IDE.
Setup Processing IDE for Seismic Graph

Download and install the Processing IDE from Processing IDE Link.
Open the Processing IDE and copy the provided Processing code into a new sketch.
Run the sketch in the Processing IDE. A seismic graph should appear on the screen.
Testing the Earthquake Detector

Shake or tilt the accelerometer to simulate earthquake movements.
Observe the LCD display on the Arduino board for status updates.
Simultaneously, monitor the seismic graph on the computer screen to visualize the detected vibrations.

Note
Ensure proper connections and power supply for accurate readings.
Customize the threshold values (maxVal and minVal) in the Arduino code as needed for your application.
The buzzer and LED serve as visual and audible indicators, but can be replaced or enhanced based on project requirements.
