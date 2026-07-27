# Autonomous Micromouse Robot for Intelligent Maze Solving

An autonomous Micromouse robot capable of exploring unknown mazes, generating a map, and finding the shortest path using PID control, Time-of-Flight sensors, encoder feedback, and gyroscope-assisted navigation.

---

## Project Overview

This project was developed by **Team Robolution** for autonomous maze solving. The robot detects surrounding walls using three VL53L0X Time-of-Flight sensors, maintains straight movement using encoder-based PID control, performs accurate 90° turns using an MPU6050 gyroscope, and autonomously reaches the destination.

---

## Features

- Autonomous Maze Solving
- Real-Time Wall Detection
- PID Controlled Straight Motion
- Encoder Feedback
- Gyroscope Based Turning
- OLED Status Display
- TB6612FNG Motor Driver
- Shortest Path Navigation
- Modular Software Architecture

---

## Hardware Used

- Arduino UNO Q
- TB6612FNG Motor Driver
- 3 × VL53L0X ToF Sensors
- MPU6050 IMU
- SSD1306 OLED Display
- 2 × N20 DC Gear Motors with Encoders
- Li-ion Battery
- Piezo Buzzer
- Status LED

---

## Software Libraries

- Wire
- Adafruit_GFX
- Adafruit_SSD1306
- VL53L0X
- MPU6050

---

## Folder Structure

```text
docs/          Documentation
hardware/      Circuit & Mechanical Design
software/      Arduino Source Code
images/        Project Images
videos/        Demo Video
results/       Testing Results
```

---

## Working Principle

1. Initialize sensors
2. Read wall distances
3. Detect open path
4. Maintain straight movement using PID
5. Turn using gyroscope feedback
6. Continue exploration
7. Generate shortest path
8. Reach destination

---

## Components

| Component | Quantity |
|-----------|---------:|
| Arduino UNO Q | 1 |
| TB6612FNG | 1 |
| VL53L0X | 3 |
| MPU6050 | 1 |
| SSD1306 OLED | 1 |
| N20 Motors | 2 |
| Wheel Encoders | 2 |

---

## Future Improvements

- Flood Fill Algorithm
- SLAM Integration
- Wireless Telemetry
- AI-based Path Optimization
- Higher Speed Motion Planning

---

## Team

**Team Robolution**

- Abhishek Gupta (Team_Leader)


---

## License

MIT License
