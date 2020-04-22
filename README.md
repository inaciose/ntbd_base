# ntbd_base
ROS common packages for robotic arms with the ntbd project

Packages:
- ntbd_core
- ntbd_msgs

Requires an arm description package for the specific robotic arm with the following scripts

- scripts/IK
- scripts/FK
- scripts/motors_values
- scripts/physical_2_visual

It also expect an urdf file for the arm and some launch files to be present in the description package. See sample for the arm description.

The robot arm motors should be controlled by an Arduino or another compatible MCU running the apropriate ntbd firmware.

Related repositories

- https://github.com/inaciose/ntbd_firmware
- https://github.com/inaciose/ntbd_web
- https://github.com/inaciose/ebamk1_description
- https://github.com/inaciose/ebamk2_description
- https://github.com/inaciose/ramk2p_description
