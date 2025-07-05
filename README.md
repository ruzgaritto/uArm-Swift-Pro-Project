# uArm-Swift-Pro-Project
A robot project.

# uArm Swift Pro - Robotic Arm Project

This project is built using the **uArm Swift Pro** robotic arm to demonstrate precise automation tasks through custom programming and control systems. The aim is to integrate hardware and software components to create a robust and intelligent robotic platform for various applications.

## 🔧 Project Overview

The project explores the potential of the uArm Swift Pro in tasks such as:

- Pick-and-place automation
- Object tracking using computer vision
- 2D coordinate mapping and workspace calibration
- Integration with sensors (e.g., OpenMV, ultrasonic, IMU)
- Real-time serial communication between PC and arm

## 🧠 Technologies Used

- **uArm Swift Pro SDK / Python API**
- **OpenMV** (for object detection / color tracking)
- **Python 3.x**
- **Serial Communication (pyserial)**
- **NumPy** & **OpenCV** (for image processing and transformation matrices)
- **Transformation Matrix Calculation** (for camera-to-arm coordinate mapping)


## 🗺️ System Architecture

```mermaid
graph TD
    Camera -->|Image Processing| PythonApp
    PythonApp -->|Coordinates| uArm
    uArm -->|Move to Position| Object
