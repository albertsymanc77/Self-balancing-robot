# Self-Balancing Two-Wheeled Robot 🤖

## Project Overview
This project focuses on the design and implementation of a self-balancing two-wheeled robot based on the inverted pendulum principle. The robot uses real-time sensor feedback and PID control to maintain its upright position by continuously adjusting motor speed and direction.

## Objectives
- Design and fabricate a two-wheeled self-balancing robot.
- Estimate tilt angle using an MPU6500 IMU sensor.
- Implement PID control for real-time balance correction.
- Apply sensor fusion using a complementary filter.
- Use encoder feedback to monitor wheel movement.

## Hardware Components
- Arduino UNO
- MPU6500 IMU sensor
- 12V DC geared motors with encoders
- Cytron dual motor driver
- Rechargeable battery
- Robot chassis and wheels

## Working Principle
The MPU6500 measures the robot's orientation using its accelerometer and gyroscope. A complementary filter combines the sensor readings to estimate the tilt angle. The Arduino UNO processes this data using a PID controller and sends control signals to the motor driver. The motors then move in the required direction to correct the tilt and maintain balance.

## Technologies Used
- Embedded C/C++ (Arduino)
- PID Control
- Sensor Fusion
- Encoder Feedback
- Robotics and Mechatronics

## Challenges Addressed
- IMU sensor noise and drift
- Motor dead zones and response differences
- Encoder signal interference
- PID tuning and system stability
- Mechanical weight distribution

## Future Improvements
- Integrate a load sensor for fall or lift detection.
- Improve motion control using encoder feedback.
- Explore wireless control and real-time monitoring.

## Project Domain
Robotics | Mechatronics | Embedded Systems | Control Systems
