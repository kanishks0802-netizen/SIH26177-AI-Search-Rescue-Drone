# AI-Powered Autonomous Search & Rescue Drone

## SIH 2026 – Problem Statement 26177

An AI-powered autonomous drone designed to assist search-and-rescue teams in disaster environments by combining autonomous navigation, multi-sensor detection, 3D mapping and real-time survivor localization.

## Problem

Disaster zones are dangerous and difficult to search manually. Collapsed structures, debris, smoke and poor visibility can delay survivor detection and put rescue personnel at risk.

## Proposed Solution

Our system uses an autonomous search-and-rescue drone equipped with:

- GPS/GNSS and IMU
- RGB camera
- Thermal camera
- LiDAR
- Edge AI processing
- Autonomous navigation
- Obstacle avoidance
- Survivor detection and verification
- Real-time geo-tagging
- 3D disaster mapping

## Key Innovation

The drone follows an adaptive search workflow:

**Initial Scan → Risk Identification → Dynamic Search → Obstacle Avoidance → Survivor Verification → Geo-Tagging → Search Memory → Return to Base**

Instead of following only a fixed route, the system can prioritize high-risk areas and adapt its search based on detected conditions.

## 3D Drone Design

The drone was designed in FreeCAD.

**CAD File:** `CAD/SIH177_Drone_V7.FCStd`

## Disaster Environment Simulation

A detailed disaster environment was developed in Blender to demonstrate:

- Autonomous flight path
- Damaged buildings
- Rubble and debris
- Smoke/hazard zones
- Survivor detection
- LiDAR visualization
- RGB and thermal sensing
- Mission HUD
- Return-to-base sequence

## Technology Stack

- FreeCAD – Drone CAD design
- Blender – 3D disaster simulation
- Python – Automation and simulation scripting
- GPS/GNSS – Positioning
- IMU – Motion estimation
- LiDAR – Mapping and obstacle detection
- RGB + Thermal – Survivor detection
- Edge AI – On-device inference

## Project Structure

```text
CAD/                 → Drone CAD design
Blender_Simulation/  → Disaster environment simulation
Screenshots/         → Project screenshots
Code/                → Scripts and implementation
Documentation/       → Project documents
Demo/                → Demonstration material
## Project Screenshots

### Drone CAD Design
![Drone CAD](01_Drone_CAD.png)

### Disaster Environment
![Drone Environment](02_Drone_Environment.png)

### Smoke Detection
![Smoke Detection](03_Smoke_Detected.png)

### Human Detection
![Human Detection](04_Human_Detected.png)

### Return to Base
![Return to Base](05_Return_To_Base.png)
