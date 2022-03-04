# AIRCRAFT-STABILITY-AND-CONTROL
Aiming to develop an effective way of auto stabilizing controller for aircraft. The whole simulation is built on MATLAB Simulink aerospace blockset, where a nonlinear model is built which is then linearized using a built-in control design function. It is then tuned using a PID controller and simulated to validate the function of the model. This simulation system plays an important role in designing and testing the control system and has made a good effect on validating the control law of the aircraft.
## Steps to use simulation model
1st Open file "fullPlant"
2nd load aeroData using command load('aeroData.mat')
3rd Run the simulink model
4th Open Simulation Data inspector
