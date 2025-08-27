# Bitumen Buddy – Semi-Autonomous Pothole Detection & Filling Robot

## Overview
Bitumen Buddy is a **semi-autonomous robot** developed as part of the **Design Practicum at IIT Mandi** for road maintenance automation.  
The robot detects potholes, estimates their volume, and dispenses filler material to repair them, while allowing RC override for operator control.  

## Features
- **4WD mobility platform** with Arduino-based motor control, GPS logging, and RC override  
- **Pothole detection** using YOLOv6 on Raspberry Pi  
- **Depth sensing & volume estimation** with Arducam ToF camera and Open3D processing  
- **Dual-servo dispensing system** for controlled material filling  
- Designed for **field deployability** with modular and robust chassis  

## Technical Stack
- **Hardware:** Arduino, Raspberry Pi, Arducam ToF Camera, Dual Servo Mechanism  
- **Software:** Python, Open3D, YOLOv6, GPS logging  
- **Design Tools:** CAD modeling (Isometric & Front views), Embedded C for motor control  

## Media
### Robot Prototype
| Full Bot | Side View |
|----------|-----------|
| ![Bot Image 1](bot1.jpg) | ![Bot Image 2](bot2.jpg) |

### CAD Renders
| Isometric | Front |
|-----------|-------|
| ![CAD Isometric](cad_iso.jpg) | ![CAD Front](cad_front.jpg) |

*(Replace the file names with your actual image paths, e.g., `images/bot1.jpg`.)*

## Project Report
📄 [Download Report (PDF)](report.pdf)  

## Skills Demonstrated
- Embedded Systems (Arduino motor control, GPS logging, RC override)  
- Computer Vision (YOLOv6 pothole detection)  
- 3D Data Processing (Arducam ToF + Open3D for volume estimation)  
- CAD Design and Mechatronic Integration  

## Future Work
- Improve real-time detection performance with optimized models  
- Enhance material dispensing precision with feedback control  
- Integrate SLAM for fully autonomous navigation  

---
