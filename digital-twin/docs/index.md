# Welcome to Documentation of Digital Twin at TCC!

> [!NOTE]
> The documentation is still WIP. The hardware and software setup is complete but not in-use.

This documentation will show the usage of the digital twin for the control and development of algorithms for controlling the two robotic arms.

The setup consists of robots: **Universal Robots** `UR10` and **Yasakawa** `HC10DT`, grippers: **Robotiq** `2f-140` and `2f-85`, and cameras **Robotiq** 2x `wrist_cameras` and 2x `zed2i` stereo cameras.

## Hardware List

| **ID** | **Manufacturer** | **Type** | **Count** |
| ----- | --- | --- | --- |
| `HC10DT` | Yasakawa | 6-axis robotic arm | 1 |
| `UR10` | Universal Robots | 6-axis robotic arm | 1 |
| `2f-140` | Robotiq | two fingers gripper | 1 |
| `2f-85` | Robotiq | two fingers gripper | 1 |
| `wrist_camera` | Robotiq | camera | 2 |
| `zed2i` | Stereolabs | stereo camera | 2 |
| `FT-300S` | Robotiq | Force Torque Sensor | 1 |

## Software

The setup uses `ROS2 Humble` for simulating and also controlling the real hardware.