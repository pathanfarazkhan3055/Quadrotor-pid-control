# Quadrotor Altitude Regulation Using PID Control in the Presence of Wind Disturbances

## Project Summary

This project focuses on the development and performance evaluation of a PID-based altitude control system for a quadrotor UAV operating under external wind disturbances.

The controller is designed to accurately maintain the desired flight altitude, suppress the effects of environmental disturbances, and stabilize a dynamically unstable system. This work was completed as part of the **AA216 – Flight Mechanics and Classical Control** course at **Indian Institute of Technology Indore**.

---

## Problem Description

Maintaining a constant altitude is challenging for quadrotor drones due to several factors:

* Wind gust disturbances ranging from 0–15 m/s
* Measurement noise from onboard sensors
* Nonlinear characteristics of motor actuators
* Intrinsically unstable open-loop flight dynamics

The primary goal of this project is to design a robust PID controller capable of delivering stable and reliable altitude regulation under these conditions.

---

## Mathematical Model

### Quadrotor Dynamics

Gp(s) = 6.25 / (s² − 2s + 6.25)

### Motor Model

Gm(s) = 20 / (s + 20)

### PID Controller

C(s) = Kp + Ki/s + Kd·s

---

## Control Design Methodology

The following classical control techniques were employed during controller development:

* PID Controller Tuning
* BIBO Stability Assessment
* Routh–Hurwitz Stability Analysis
* Root Locus Design
* Frequency Response Analysis using Bode Plots
* Steady-State Error Evaluation
* MATLAB/Simulink Simulation and Validation

---

## Optimized PID Parameters

| Parameter | Value |
| --------- | ----- |
| Kp        | 3.0   |
| Ki        | 1.5   |
| Kd        | 0.8   |

---

## Performance Results

| Performance Metric | Result              |
| ------------------ | ------------------- |
| Steady-State Error |  ~0%    |
| Rise Time          |  ~1.4 s |
| Maximum Overshoot  |  ~0.3 m |
| Settling Time      |  ~2.1 s |
| Phase Margin       |  ~58°   |
| Gain Margin        |  ~11 dB |

The implemented PID controller successfully achieved closed-loop stability, minimized altitude tracking error, and demonstrated strong rejection of wind-induced disturbances.

---

## Potential Applications

* Autonomous Package Delivery UAVs
* Agricultural Monitoring and Spraying Drones
* Structural Inspection Platforms
* High-Precision Hovering and Surveillance Systems

---

## Repository Structure

* Final Project Report (PDF)

---


**Pathan Farazkhan Hushenkhan**

**Indian Institute of Technology Indore**

**AA216 – Flight Mechanics and Classical Control**
