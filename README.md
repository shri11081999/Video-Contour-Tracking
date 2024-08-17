# 🎨 Video Tracking by Finding Contour of Interest and Using Paint Application to Show Path

![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5+-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project combines real-time video tracking and a painting application using OpenCV. We track objects by finding contours and visualize their paths through painting.

## Contour of Interest tracking - ![gif1](https://github.com/user-attachments/assets/fb9c380d-a121-469f-a4c5-aa2ec714a155)

## Path Mapping using Paint Application - ![gif2](https://github.com/user-attachments/assets/cb29ec96-6748-46e6-8563-7d7a5705e590)



## 📚 Table of Contents
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Features](#features)
- [Requirements](#requirements)
- [Setup and Usage](#setup-and-usage)
- [Project Structure](#project-structure)
- [Evaluation and Results](#evaluation-and-results)
- [Applications](#applications)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)

## 🌟 Introduction
This project showcases **video tracking** using contours and visualizes object movements with a simple **painting application**. Developed with **OpenCV**, it tracks moving objects, extracts contours, and draws their paths on a canvas.

**Key Technologies**:
- Python 3.6+
- OpenCV (Computer Vision Library)
- Real-time Object Tracking

## 💡 Motivation
This project was inspired by the increasing use of **video tracking** in areas like **surveillance**, **gaming**, and **AI applications**. Systems like the Wii Remote and Kinect have revolutionized user interaction through tracking technology, and this project explores how similar methods can be implemented using Python and OpenCV.

## ✨ Features
- **Real-time Contour Detection**: Detect and track contours in video frames.
- **Path Visualization**: The tracked object’s path is visualized on a paint canvas.
- **Multi-color Support**: Different colors can be used for different objects.
- **User Interface**: Simple UI using rectangles and text for easy color selection.

## 🛠️ Requirements
To run this project, you’ll need the following dependencies:
- Python 3.6+
- OpenCV 4.5+
- Numpy

## 🚀 Setup and Usage
1. Clone the Repository

Install the dependencies using:
``bash
git clone https://github.com/yourusername/video-tracking-paint.git
cd video-tracking-paint```

2. Run the Application:

3. Using the Paint Interface:
** Select a color by clicking on the color rectangles at the top.
** Start moving the object in front of your webcam to track and paint.

## 🧪 Evaluation and Results

This project demonstrates effective real-time object tracking and contour detection. Here are some highlights of the evaluation:

1. **Contour Detection**: The algorithm can successfully detect contours of objects even in challenging conditions, such as dim lighting or complex backgrounds.
2. **Path Visualization**: The project visualizes the object's movement by drawing its path on a virtual canvas, which updates in real-time.

## 🎯 Applications

This project has a wide range of applications, including:

1. **Artificial Intelligence**: AI systems can use the algorithm for object recognition, tracking, and path mapping.
2. **Surveillance**: The technology can be applied to track suspects' movements and analyze paths in surveillance footage.
3. **Medical Imaging**: It can be used to differentiate between tissues or detect abnormalities in medical scans.
4. **Self-Driving Cars**: Track objects on the road and use the path tracking to aid in navigation.
5. **Gaming**: Develop interactive, motion-tracking based games or systems.

The potential uses for this technology are broad and can extend to any domain that requires real-time object tracking and path visualization.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
