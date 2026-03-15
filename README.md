# PendulumRover

Self-balancing camera rover based on M5Stack.

Overview

PendulumRover is a self-balancing robot controlled as a remote vehicle.
It uses an inverted pendulum control system and streams camera video for remote operation.

Hardware

- M5Stack CoreS3
- M5Stack Unit CamS3 5MP
- ROBOTIS Dynamixel Roller-485 ×2

Architecture

Smartphone
→
CamS3 (Camera + Web UI)
→
CoreS3 (Balance Control)
→
Roller485 Motors

Features

- Inverted pendulum stabilization
- Camera streaming
- WiFi remote control

Development Steps

1. Build independent balancing rover
2. Implement camera controller
3. Connect controller and rover
4. Remote control with camera view

Future Work

- Autonomous navigation
- Visual tracking
- SLAM
