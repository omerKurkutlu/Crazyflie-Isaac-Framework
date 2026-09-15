# CIF — Crazyflie Isaac Framework

### A Modular NVIDIA Isaac Sim Framework for Crazyflie Research

CIF is a modular simulation framework built on **NVIDIA Isaac Sim** for developing, testing, and evaluating autonomous algorithms for the **Crazyflie micro aerial vehicle**.

<p align="center">
  <img src="assets/cif_brochure.png" width="100%">
</p>

## About CIF

CIF provides a flexible research environment for Crazyflie autonomy, allowing researchers to rapidly integrate and evaluate new perception, planning, control, and learning algorithms before real-world deployment.

The framework is designed around a modular architecture, allowing individual components—including inputs, controllers, sensors, environments, and autonomous algorithms—to be independently configured, replaced, or extended.

## Key Capabilities

- 🎮 **Dual Controllers** — Position (waypoint) and velocity/manual control
- 🔌 **Plug-and-Play Inputs** — Joystick, CSV, terminal commands, and neural-network outputs
- 📷 **Sensor Integration** — RGB camera and Multi-Ranger sensing
- 🧩 **Modular Architecture** — Easily replace or extend controllers, sensors, mixers, and algorithms
- 🌎 **Environment Management** — Load Isaac Sim environments or integrate custom USD worlds
- 🤖 **Sim-to-Real Research** — Designed with physical Crazyflie deployment in mind

## Research Applications

CIF is intended to support research in:

- Autonomous Navigation
- Monocular Depth Estimation
- Vision-Based Control
- Sensor Fusion
- Local Occupancy Mapping
- Deep Reinforcement Learning
- TinyML / Edge AI
- Multi-Drone Systems
- Sim-to-Real Transfer
- Robotics Benchmarking

## Project Status

> 🚧 **CIF is currently under active development.**

This repository currently serves as the public project page for CIF.  
The complete framework, documentation, installation instructions, and examples will be released as development progresses.

## Developed at

**Resilient Ubiquitous Intelligence Computing (RUIC) Lab**  
University of Illinois Chicago

---

**CIF — Crazyflie Isaac Framework**  
*Develop. Simulate. Deploy.*





🎥 Demo
Multi-Drone Navigation with Randomized Start and Goal Positions

This demonstration shows four Crazyflie drones operating simultaneously in NVIDIA Isaac Sim using CIF.

Each drone is initialized with a randomized starting position and assigned a randomized target position within the environment.

The simulation visualizes:

🚁 Four simultaneously simulated Crazyflie drones
🎯 Randomized target positions represented by spheres
📡 Multi-Ranger sensor measurements around each drone
➖ Drone-to-target lines for visualizing individual navigation objectives
🤖 Independent navigation toward assigned targets

▶️ Watch the demo on YouTube




Multi-drone navigation demonstration using the Crazyflie Isaac Framework (CIF).
