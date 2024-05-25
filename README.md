# Automatic-Handraise-detection-Application
# OVERVIEW
This repository contains a React application that integrates TensorFlow.js to detect and analyze hand rise detection in real time. The application demonstrates the potential of machine learning in interactive web environments and can serve as a basis for developing interactive games, accessibility tools, or advanced user interfaces.
# Features
# Detection of Handrise-
  Whenever the person in the frame rises the hand for a query, it is detected.
# Blink of handrise emoji
   Whenever the hand rise in real time is detected, the hand rise emoji is blinked.

# Prerequisites
 To run this application, you will need:

1)Node.js (version 14.0.0 or higher recommended)
2)npm (version 6.0.0 or higher recommended)
3)A webcam
4)A modern web browser with TensorFlow.js support

# Installation Instructions

# 1. Clone the Repository
git clone https://github.com/Sneha-Ponduri/Automatic-Handrise-detection-Application.git
cd Automatic-Handraise-detection-Application

# 2.Install dependencies
npm install

# 3. Run the Development Server
npm start

After starting the server, open your web browser and go to http://localhost:3000. The application should be running, and you should be prompted to allow webcam access.

# Usage Guide

To use the application:

Allow the application to access your webcam when prompted.
The main interface will display your video stream.
Raise your hand.

# Technology Stack
React: For building the user interface.
TensorFlow.js: For facial detection and interaction capabilities.
Webcam Capture: Uses the HTML5 video API to capture video from the user's webcam.

# Code Structure Overview
src/: Source directory for all the project code.
App.js: Main React component integrating TensorFlow.js and managing state and UI.
src/components/FaceDetection.js: TensorFlow.js models and logic for facial interaction detection.
utils/: Utility functions to support various application operations.

# License
This project is released under the MIT License, which allows modification and redistribution for both personal and commercial purposes. See the LICENSE file in the repository for full details.

# Contact Information
- Sneha: snehaponduri@gmail.com
- GitHub Project URL: https://github.com/Sneha-Ponduri

- LinkedIn Profile URL: https://www.linkedin.com/in/sneha-ponduri-8035892a9/

