# Physics-Based-Modeling-of-nBn-HgCdTe-Infrared-Detector
Project Overview

This project presents a MATLAB-based physics-oriented computational model of dark current in an nBn HgCdTe (Mercury Cadmium Telluride) infrared detector.

The simulation investigates the major dark-current components and their dependence on temperature, reverse bias, and nBn barrier height. The model combines several simplified physical mechanisms to calculate the total dark current and compares the modeled behavior of conventional HgCdTe and nBn HgCdTe detectors.

Dark-current mechanisms modeled
Diffusion current
Shockley–Read–Hall (SRH) current
Trap-Assisted Tunneling (TAT) current
Auger current
Total dark current
nBn barrier-modified dark current
The project is intended for semiconductor device physics, infrared detector modeling, and MATLAB-based research simulation.

The main objectives of this project are:

Model the temperature-dependent bandgap of HgCdTe.

Calculate diffusion dark current over the temperature range of 77–300 K.

Model Shockley–Read–Hall dark current.

Investigate Trap-Assisted Tunneling under reverse bias.

Study the temperature dependence of TAT current.

Model Auger dark current.

Combine the individual mechanisms to obtain total dark current.

Introduce an nBn barrier and analyze its influence on dark current.

Study the relationship between barrier height and dark current at 77 K.

Compare conventional HgCdTe and modeled nBn HgCdTe dark-current behavior.

 Material and Device Parameters
 
The simulation uses a HgCdTe material with the following Cd composition:
x = 0.23;
The temperature range is:
T = 77:5:300;

Therefore, the model evaluates detector behavior from 77 K to 300 K.

The detector thickness used for the electric-field calculation is:
d = 5e-4;     % cm which corresponds to 5 μm.

Reverse Bias	0–0.5 V

Example Barrier Height	0.20 eV

Barrier Sweep	0–0.40 eV

Key Results

The simulation provides a computational framework for studying:

Temperature-dependent HgCdTe bandgap

Diffusion dark current

SRH dark current

Trap-assisted tunneling

Auger current

Total dark current

nBn barrier effects

Barrier-height dependence at 77 K

Conventional versus nBn dark-current behavior

The barrier-height sweep also identifies the barrier value corresponding to the minimum modeled 77 K dark current within the selected range.
