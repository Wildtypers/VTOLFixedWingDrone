# VTOLFixedWingDrone
© 2026 Kelvin Huang. All rights reserved. Unauthorized copying, modification, or redistribution of this project is strictly prohibited.

This project is a hybrid VTOL (Vertical Takeoff and Landing) fixed-wing drone designed to combine the hovering and vertical takeoff capabilities of a multirotor with the efficiency and high-speed forward flight of a fixed-wing aircraft. The drone is intended as a platform for experimental hybrid flight dynamics, autonomous operation, and advanced drone control techniques.

Key features:

Two tilt-capable vertical lift rotors for VTOL and omnidirectional movement.

Two forward-facing motors on each wing for efficient cruise flight.

Smooth transitions between hovering, forward flight, and lateral movement.

Optimized airframe for balance, weight, and aerodynamic stability.

Full autonomous flight capability with waypoint navigation and precision control of motors and aerodynamic surfaces.


Hardware Components

Flight Controller: Matek H743-WLITE (STM32H743VIH6)

Supports 4 motors + multiple servos.

Built-in OSD, Blackbox logging, and microSD slot.

Compatible with ArduPilot firmware for hybrid VTOL/fixed-wing operations.


Motors:
2 vertical lift rotors (tilt-capable).

2 forward-facing motors on each wing for cruise flight.



ESCs (Electronic Speed Controllers): One per motor, connected via PWM signal pads on the flight controller.


Servos: For tilt mechanisms of vertical rotors and aerodynamic control surfaces (ailerons, elevator, rudder).


Sensors:

GPS module for autonomous navigation.

Optional telemetry modules for real-time flight data.

Optional airspeed or range sensors for flight control optimization.

Power System: LiPo battery (3–8S) powering ESCs and flight controller. Built-in BEC provides regulated voltage to servos and sensors.
