# PID Control of Quadrotor Altitude Stabilization Under Wind Gust Disturbances

## Project Description

This project investigates the development of a PID-based control strategy for maintaining stable altitude in a quadrotor unmanned aerial vehicle (UAV) subjected to environmental disturbances. The study focuses on enhancing flight stability, improving altitude tracking accuracy, and minimizing the impact of external factors such as wind gusts and system uncertainties through classical control techniques.

The complete controller design and performance analysis were carried out using MATLAB and Simulink as part of the AA216: Flight Mechanics and Classical Control course at IIT Indore.

## Objective

The primary goals of this project were:

- Stabilize an inherently unstable quadrotor altitude system
- Maintain accurate reference tracking under varying conditions
- Reduce the influence of external disturbances
- Improve transient and steady-state performance
- Evaluate controller robustness using classical control methods

## Mathematical Model

### Quadrotor Dynamics

Gp(s) = 6.25 / (s² − 2s + 6.25)

### Motor Model

Gm(s) = 20 / (s + 20)

### Controller Structure

C(s) = Kp + Ki/s + Kd·s

## Methodology

The controller design process involved:

- Dynamic system modeling
- PID gain tuning
- Stability verification
- Frequency-domain analysis
- Time-domain response evaluation
- MATLAB/Simulink-based simulation studies

## Analytical Techniques

- Root Locus Design
- Routh-Hurwitz Stability Test
- BIBO Stability Analysis
- Bode Frequency Response Analysis
- Steady-State Error Evaluation
- Closed-Loop Performance Assessment

## Optimized PID Parameters

| Parameter | Value |
|-----------|--------|
| Kp | 3.0 |
| Ki | 1.5 |
| Kd | 0.8 |

## Performance Metrics

| Parameter | Result |
|------------|---------|
| Steady-State Error | ~0% |
| Rise Time | ~1.4 s |
| Overshoot | ~0.3 m |
| Settling Time | ~2.1 s |
| Phase Margin | ~58° |
| Gain Margin | ~11 dB |

## Key Outcomes

- Achieved stable closed-loop altitude regulation
- Demonstrated effective rejection of wind-induced disturbances
- Improved transient response characteristics
- Maintained high tracking accuracy
- Verified controller robustness through simulation-based validation

## Practical Applications

- Autonomous UAV Navigation
- Aerial Surveillance Systems
- Precision Agriculture Drones
- Infrastructure Monitoring
- Delivery and Logistics UAVs
- Intelligent Flight Control Systems

## Repository Contents

- Detailed Project Report
- MATLAB Scripts
- Simulink Models
- Simulation Outputs
- Performance Analysis Results

## Team Members

- Faraz Khan
- Akash Kumar Gupta
- Piyush Rathore
- Anurag Krishnan

## Institution

Indian Institute of Technology Indore

AA216 – Flight Mechanics and Classical Control
