# 🤖 Robotic Arm With Flex Sensor

This project demonstrates a robotic arm controlled through finger gestures using **self-made flex sensors**. The system maps finger bending to corresponding movements in a robotic arm using Arduino and servo motors.

## 🔧 Hardware Used
- Arduino Uno  
- Custom-built Flex Sensors   
- Servo Motors   
- Jumper Wires  
- Breadboard  
- 3d Print of Robotic Arm Frame 

## 💡 Key Features
- Real-time gesture-based control of robotic arm
- Flex sensors made from scratch using low-cost materials
- Smooth and responsive servo movement through mapped analog values
- Modular and easy-to-replicate setup

## 📐 Working Principle
1. Flex sensors generate variable resistance based on finger bending.
2. Arduino reads analog values from each sensor.
3. The code maps sensor values to corresponding servo angles.
4. Servo motors move robotic arm joints in sync with finger gestures.

## 🧠 Code Highlights
- Analog input handling from flex sensors
- Servo motor angle mapping using `map()` function
- Calibration logic to adjust for sensor sensitivity







