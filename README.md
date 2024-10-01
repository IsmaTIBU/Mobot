# MoBot - Mobile Robot

The only program that can be tested without this hardware is the image recognition program “balltracking.py” that tracks colored balls , which will use a computer's default camera. Depending on the camera used, results may vary.This program is intended to be used with a Picamera2. It also works well with my collegue's Acer laptop camera.

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

## Some results illustrated by video
1.**Real-time video stream image processing**:
Here we were doing some tests on how the camera on robot would detect the ball and if it would detect it correctly. You can see a red trail every time we move the ball, following its center.
[Watch video](https://github.com/user-attachments/assets/0bd85940-c4d1-4439-9bbd-5f775ef4f498)

2.**Voice Command Interpretation**:
In this video we mainly wanted to demonstrate that even if the user asks the robot to perform impossible tasks in certain scenarios, it is able to always keep in mind that its integrity comes first and will activate an obstacle avoidance protocol. However, this way you can also watch how the voice command interpretation works.
[Watch video](https://github.com/IsmaTIBU/Mobot/blob/main/Video_MoBot_2.mov)

3.**Robot scanning in autonomy**:
The purpose of the robot in this task is to scan a room without crashing with the walls.
[Watch video](https://github.com/user-attachments/assets/4f919ec4-3920-405f-a559-740e681eeb6c)


