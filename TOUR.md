# A short tour of my HARP work

I contribute navigation, motion control, and development tools to HARP's human interaction team.

## 1. Waypoint navigation

[PR #2: Waypoint routes and runtime safeguards](https://github.com/Humanoid-Athletic-Robotics-Project-HARP/social-interaction/pull/2)

Added configurable waypoint routes and repeated laps to the simulator course runner, with manual takeover, bounded navigation requests, and fault handling.

The contribution also improved sensor freshness checks and the handling of run records. Validation included automated tests and recorded simulator runs.

## 2. Waypoint recording and speed control

[PR #5: Waypoint recording and speed smoothing](https://github.com/Humanoid-Athletic-Robotics-Project-HARP/social-interaction/pull/5)

Added an interactive tool that records positions and headings from ROS 2 odometry, supports undo, and saves reusable route files.

Straight-distance walks now ramp speed requests and slow near the target. Completion, timeout, and fault handling still request an immediate stop.

Local ROS 2 tests cover these changes. Target-image execution, simulator behavior for the latest changes, and physical robot behavior still need validation.

## Explore the team project

The [HARP repository](https://github.com/Humanoid-Athletic-Robotics-Project-HARP/social-interaction) documents the full team system, setup, progress, and validation limits.

[Back to my profile](README.md)
