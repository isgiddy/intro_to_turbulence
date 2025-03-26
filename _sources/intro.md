# An introduction to observing turbulence in the ocean

This module was developed by Isabelle Giddy for the University of Gothenburg Department of Marine Sciences Masters level course OC4920: Observing the ocean from macro to micro scale *(Version 1, Copyright 2025)*. I'd like to acknowledge my own teachers in ocean turbulence, Prof Ilker Fer, Dr. Lars Arneborg and Dr. Daniel Whitt who have in some way informed the content of this module. I am gratefully hosted at the University of Gothenburg Marine Sciences Department and supported by the VR International Postdoctoral Grant and the Prof Sebastiaan Swarts Wallenberg Academy Fellowship, which make being an independent researcher possible. 

The module is given over 4 days and provides a brief introduction to turbulence and its application in oceanography. 

**Assignment**  
The goal of the accompanying assignment is to become familiar with working with and interpreting observations of the rate of dissipation of turbulence. 
The assignment is presented in Python, and while any coding language of preference can be used, the easiest would be to ensure that you have an updated version of python working on your local machine with the following dependencies: numpy, matplotlib, pandas, xarray (including h5netcdf) and gsw.
An environment.yml file is provided which will install all nessecary dependencies provided you have the Anaconda distribution installed. 
From your terminal, run ```conda env create -f environment.yml```, then ```conda activate turbulence```

Completion and submission of the assignment is nessecary for completing the course. 

**Reading**  
A few texts are recommended for further reading. Other relevent references are given throughout.

Ocean Mixing {cite}`ocean_mixing`  
Introduction to Ocean Turbulence {cite}`thorpe_2007`  
Three-dimensional (3D) turbulence {cite}`smyth_2009`  

---

These notes may be updated during the course. 


## Learning Goals

After working through this material, students should have the ability to:

- Define turbulence 
- Understand the Turbulent Kinetic Energy budget 
- Characterise turbulent flows
- Gain familiarity with methods for observing turbulence in the ocean
- Understand and describe the role of turbulent flow in the ocean
