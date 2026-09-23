# EEE_306_PROJECT
Optimal Multi-Stage Capacitor Placement and Control Algorithm

This MATLAB project implements an optimal multi-stage capacitor placement and control algorithm for the IEEE 33-bus distribution system. It uses sensitivity indices to select capacitor locations and sizes offline, then applies a greedy dispatch method refined by Particle Swarm Optimization (PSO) to actively manage hour-by-hour switching over a 24-hour load profile. The algorithm minimizes daily energy losses and improves voltage stability while strictly enforcing limits on daily switching operations to prevent equipment wear, ultimately comparing the performance of uncompensated, fixed, and dynamically switched capacitor configurations.
