# Robotic-simulation--course-work-2-
This is the course work of the module Artificial life with Robotics  7COM1032-0901-2024Assignments
Unity Robot Controller Coursework
This project contains a C# script developed for university coursework to autonomously control a robot in Unity. The code utilizes built-in Raycast sensors (FRS, L1S, L2S, L3S, R1S, R2S, R3S) for obstacle and road detection, and the ORS for robot orientation feedback.
Robot wheel movement is managed using WheelCollider for each wheel and transform synchronization.
Navigation logic is handled in physics updates (FixedUpdate) for smooth, realistic movement while adhering to model and assessment constraints.

Key features:

Autonomous track following using proximity sensors

Obstacle avoidance and real-time steering adjustments

Modular functions for sensor setup, power/steering, and wheel pose

Optimized for Unity physics and educational review
