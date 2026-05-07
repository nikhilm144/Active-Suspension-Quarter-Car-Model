Active Suspension System using Simulink & Simscape
Overview
This project implements a Quarter Car Active Suspension System using MATLAB Simulink and Simscape.
The model simulates how an active suspension system improves ride comfort by using:
	sensors, 
	feedback control, 
	and an actuator 
to reduce vehicle body oscillations caused by road disturbances.
________________________________________
Project Objectives
The goal of this project is to:
	Model a quarter-car suspension system 
	Reduce body oscillations using feedback control 
	Understand real-world suspension dynamics 
________________________________________
System Architecture
The system consists of:
1. Sprung Mass
Represents the car body.
2. Unsprung Mass
Represents the wheel and axle assembly.
3. Tire Spring
Models tire stiffness.
4. Suspension Spring & Damper
Models passive suspension behavior.
5. Active Actuator
Applies controlled force between wheel and car body.
6. Motion Sensor
Measures car body velocity.
7. PID Controller
Generates actuator force based on velocity feedback.
________________________________________
Parameters Used:
Sprung Mass	M_s: 300 kg
Unsprung Mass M_u:40 kg
Suspension Stiffness K_s: 16000 N/m
Suspension Damping	B_s: 1000 Ns/m
Tire Stiffness	K_t: 190000 N/m
________________________________________
Road Disturbance
The road profile is modeled using a step input representing a road bump.
________________________________________
Results
Observations
	Car body displacement showed damped oscillations and stabilized within approximately 2 seconds. 
	Car body velocity stabilized within approximately 3 seconds. 
	Actuator force behaved inversely to body velocity, indicating proper negative feedback damping behavior. 
	The active suspension significantly reduced oscillations compared to passive suspension behavior. 
________________________________________
Key Learnings
This project helped in understanding:
	Quarter car dynamics 
	Mass-spring-damper systems 
	Simscape physical modeling 
	Feedback control systems 
	PID controller implementation 
	Active damping concepts 
	Sensor-actuator interaction 
	Automotive suspension dynamics 
________________________________________
Software Used
	MATLAB 
	Simulink 
	Simscape 
________________________________________
Future Improvements
Possible future extensions include:
	LQR controller implementation 
	State-space control 
	Skyhook suspension control 
	Model Predictive Control (MPC) 
	Full car suspension model 
	Random road profile simulation 
	Suspension travel optimization 
	Ride comfort analysis using acceleration metrics 
________________________________________

Applications
Active suspension systems are widely used in:
	luxury vehicles, 
	high-performance cars, 
	military vehicles, 
	autonomous vehicles, 
	and advanced EV platforms. 
________________________________________
Author
Nikhil Madhu


