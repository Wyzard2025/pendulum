# Pendulum
A mechatronic pendulum with minimal sim-to-real gap.
The pendulum is perhaps the simplest nonlinear mechanical system that commonly appears in real-world systems. Therefore, the pendulum serves as an excellent baseline for comparing algorithms in the fields of control theory, state estimation, computer vision, and robotic perception. If any algorithm doesn’t work on the pendulum, it most likely won’t work on more complicated systems.

Goals:
High-frequency, high-resolution sampling (of state and control inputs).
Easy and open software interface: open-source and easy to: use, customize, de-bug, modify, and iterate upon.
Torque-controlled motor: Motor is torque controlled and does not have a gearbox to minimize reflected inertia and modeling error. 
Accurately known physical properties: Mass, inertia, length, spring constant, viscous friction, static and kinetic dry friction. 
Noiseless, full-state measurements: position, velocity, torque, voltage, and current.
Long-term operation: The motor is able to operate for several hours without overheating.
Fault detection: Overheating or overcurrent to the motor is monitored and detected.
