# Autonomous Landing of Quadrotor based on Computer Vision
The purpose of this project is to have the drone perform a landing pad detection procedure and subsequent auto-landing under conditions such that ArUco fiducials cannot be detected.

Specifically, the objectives of the project are:

- Landing platform detection for heights where ArUco fiducials cannot be identified.
- Automatic landing from a generic initial position where the platform is detectable but the fiducials are not. The drone will have to arrive at a position such that it is able to detect the fiducials.
- The drone will have to be able to find the platform again in case due to adverse phenomena the marker should disappear from the camera FOV.
-he drone will have to perform a search maneuver for the platform in case an automatic landing is to be performed even though it has not yet seen the platform in the current scenario.


![image](https://github.com/CatInTheRain/UAV_landing/assets/55113554/1dc4b207-09a8-4fad-b895-5975f5e7d29f)

![image](https://github.com/CatInTheRain/UAV_landing/assets/55113554/676d00be-b455-4b51-9b22-46b113d03ba5)

When centering on the marker in the horizontal plane, following control actions in velocity, the backhoe body rotates in roll and pitch. In the camera image, an apparent motion of the platform originates, and this generates unwanted oscillations in the references for centering.
To overcome this phenomenon, the references to be sent to the controller, in order to generate the desired control velocities, must undergo compensation according to 𝝋 and 𝝑 angles.

![image](https://github.com/CatInTheRain/UAV_landing/assets/55113554/a3bef97d-81d7-4cf6-9fda-5ffdc9799622)

Software-in-The-Loop Simulation running in Unity

![image](https://github.com/CatInTheRain/UAV_landing/assets/55113554/96d0fe8a-ba62-4b41-bcd3-6385f3c818b6)



https://github.com/CatInTheRain/UAV_landing/assets/55113554/8c0e2e64-54ea-4b44-b4dc-30159d4f0e99

Real Experiment with Drone hardware



https://github.com/CatInTheRain/UAV_landing/assets/55113554/ac6d7453-0acd-470a-b684-f74f3b6b2afa



The complete report and code are available and can be requested in private.

