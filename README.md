# MoBot - Mobile Robot

This program is intended for use on a mobile robot with a specific motor and sensors. The only program that can be tested without this hardware is the image recognition program “balltracking.py” that tracks colored balls , which will use a computer's default camera. Depending on the camera used, results may vary.This program is intended to be used with a Picamera2. It also works well with my collegue's Acer laptop camera.

---

## Overview
The aim of this project is for the robot to become fully autonomous by allowing it to receive verbal instructions from the user to execute them when sent. For this we have used the MoBotSim program that processes verbal commands in text form and modifies them so that they can be sent via serial communication to the robot. In addition, for word analysis we had to use WhisperAI in python and link it with the previous program.

### Key Features

MoBot offers three core functionalities:

1. **Real-time video stream image processing**
   - Tracs a ball in the video stream in real time and detects it's color:

2. **Voice Command Interpretation**
   - Interprets user vocal commands thanks to an AI and uses that text transcription to deduce the corresponding actions to be performed by the robot.
      -  Languages : French

3. **Robot Movement**
   - Code located in the Arduino capable of linking different instructions with the movements having to be executed by the robot

---

## Some results
1.**Real-time video stream image processing**:[Décrire test réalisé]


2.**Voice Command Interpretation**:[Décrire test réalisé]
