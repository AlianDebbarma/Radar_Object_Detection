# Radar_Object_Detection

This project simulates a basic radar system using Arduino and Processing IDE. It uses an ultrasonic sensor mounted on a servo to scan a 180° area and visualizes detected objects on a radar-style interface.

## 🧰 Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- Arduino uno Cable
- Breadboard and Jumper Wires

## 💻 Software Used
- Arduino IDE
- Processing IDE
- Servo Library for Arduino

## 🚀 Features
- Scans 180° with 1° resolution using a servo.
- Measures distance using ultrasonic pulses.
- Sends angle and distance via serial to Processing.
- Displays a real-time radar interface with red blips for objects.

## 📷 Demo Image
![Radar Demo Image](Radar-Object-Detection/Images/radar2.jpg)
📽️ [Watch Demo Video](https://drive.google.com/file/d/1gGQ3WZd-kdcZeF58dnj2iXMMFxcitkBx/view)


## 📂 How to Run
1. Upload the Arduino code (`Radar.ino`) to your board.
2. Open `Radar_Ali.pde` in Processing IDE.
3. Select the correct serial port in Processing.
4. Run the sketch to start the radar visualization.


