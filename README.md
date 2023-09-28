# Finger-Counter
Welcome to the MediaPipe-based Finger Counting Computer Vision Model and Interactive Game repository. This project leverages the MediaPipe framework to develop a computer vision model capable of accurately counting the number of fingers displayed by the user's hand in real-time. It also includes an interactive game component where the system prompts the user to replicate the number correctly.

# Project Description
# Finger Counting Algorithm
The core functionality of this project revolves around the accurate counting of fingers on the user's left hand. The MediaPipe framework provides hand tracking and landmark estimation capabilities, which are harnessed to identify the position and orientation of each finger. ![git7](https://github.com/nourhenehanana/Finger-Counter/assets/93352403/1cd99b02-3831-4443-b6f2-204eef254a51)

# Interactive Game
One of the key features of this project is its interactive game component. The system prompts the user to accurately replicate a randomly generated number using their fingers. The computer vision model continuously processes video input from the user's camera, detects the hand, counts the fingers, and compares the count to the target number. 
Here we can see the example where the system suggest the number 23, so the user should perform its digits correctly (2 then 3) as it is shown in the images. 
![cap51](https://github.com/nourhenehanana/Finger-Counter/assets/93352403/4858bb07-4bba-4cef-acdc-27142b668028)  ![cap52](https://github.com/nourhenehanana/Finger-Counter/assets/93352403/06e70b97-44e7-436d-ba1d-001a1c117d9e)



# Real-time Interaction
The game provides real-time interaction, where the user's performance is immediately assessed. The results are displayed on the screen, indicating whether the user correctly replicated the prompted number.

# Getting Started
To get started with this project, follow these steps:

Install Dependencies: Make sure you have all the necessary dependencies installed. You need libraries such as MediaPipe, OpenCV, NumPy, and any additional dependencies required for the interactive game.

Run the Application: Execute the main application script to start the finger counting computer vision model and the interactive game. Ensure that your camera is accessible for real-time video input.

Play the Interactive Game: Follow the system prompts to replicate the prompted number using your fingers. Receive immediate feedback on your performance.


