![dynosaur](https://github.com/lcheng29/SFSU-Dynamomter/assets/124946730/fa4b539f-1c0a-489f-b17d-55938dab54c7)

The goal of this project is to design a compact dynamometer to measure the rotational power and efficiency of brushless AC motors used in RC and PEV applications.

The objectives for this project is to be accessible, simple to use with minimal intervention from the end-user, and capable of measuring torque with a resolution of 0.01 Nm.

VESC Tool will be used as the open-source platform for our tested drivetrain, as well as providing features such as controlling the motor at different RPMs and torques, verifying power data against our custom sensors, etc.

MATLAB (potentially LabView as well) will be used to access our data acqusition device, generate script to process power data, and generate efficiency plots of our sample motor. Later plans may convert the code and DAQ functions to Python for better accessibility.

Strain gauges will be used to measure the strain of a torsioned shaft. The small output signal will be boosted and denoised by an instrumentation amplifier. Slip rings will be used to transmit torque data from the gauges as the shaft is rotating.
