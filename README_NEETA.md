# Unitree ROS - GSoC 2026 Fork

Forked as part of GSoC 2026 ArduHumanoid project.

## What I studied

H1 has 5 DOF per leg: hip yaw, hip roll, hip pitch, knee, ankle.
Plus 4 DOF per arm and torso/neck. 19 DOF total (no hands).

This informed the AP_Biomimetic schema design which needs to handle
arbitrary DOF counts, not hardcoded joint names.

## Related

- Project repo: https://github.com/Neetagrg/humanoid-ardupilot-sitl
