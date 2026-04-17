
# Autopilot Landing System Development, and Controller Implementation

---

<img src="images/Runway.jpg?raw=true"/>

### Task

In my postgraduate studies at the University of Glasgow, I was tasked with designing a state space model of an autopilot landing system, creating a continuous time simulation of the model in MATLAB and Simulink, and then implementing a control system using various methods to improve the performance of it.

### Actions

- From first principles, I developed a mathematical model for the system and then converted it into a state space model.

- After appropriate step size was chosen, the model was successfully implemented into a continuous time simulation in MATLAB and Simulink.

- Coupler gain refined, and implementation of integral term to create a PI controller for the MATLAB and Simulink systems.

- Interpolation allows for the range of the aircraft to be considered by creating a formula to consider it and then the velocity of the craft is varied to see the results.

### Results

- The implementation of the mathematical model was successful however, the response was underdamped.

- The implementation of the PI controller and refinement of those values created a perfectly damped response that reached steady state in both MATLAB and Simulink.

- The interpolation stage overdamped the system, and made the response not reach steady state, but varying the aircraft velocity to 55m/s made it reach steady state again.

### Technical Considerations

- **MATLAB** and **Simulink**: Where mathematical models are implemented into a continuois time simulation and refined.
