Project Overview
This project focuses on determining the natural frequencies and mode shapes of a two-degree-of-freedom (2-DOF) spring–mass system using mass and stiffness matrix formulation and eigenvalue analysis in MATLAB.
The natural frequencies are obtained when:
• The dynamic equilibrium equation  is satisfied
• The determinant condition  produces non-trivial solutions.[M]{\ddot{x}} + [K]{x}} = 0
This project demonstrates how matrix formulation and computational tools can be used to analyze vibration behavior of mechanical systems efficiently using MATLAB.
→ Objective
The main objectives of this project are:
• To understand the concept of free vibration in multi-degree-of-freedom systems
• To formulate mass and stiffness matrices
• To apply eigenvalue analysis
• To compute natural frequencies and mode shapes

Problem Description
A two-degree-of-freedom spring–mass system consisting of:
• Two masses
• Three linear springs
• Fixed supports is analyzed to determine its natural frequencies and vibration response.
The system parameters used are:
• m₁ = 4 kg, m₂ = 2 kg
• k₁ = 2000 N/m, k₂ = 3000 N/m, k₃ = 1000 N/m
The system is assumed to be:
• Undamped
• Linear
• Free vibration (no external force)



Methodology
The natural frequencies are determined using the following computational approach:
Define mass and stiffness values
Construct mass matrix [M]
Construct stiffness matrix [K]
Solve generalized eigenvalue problem using MATLAB
Compute ω = √λ
Convert rad/s to Hz
Plot natural frequency graph
Plot vibration time response

MATLAB Implementation
The MATLAB script performs:
• Definition of system parameters
• Formation of mass and stiffness matrices
• Eigenvalue solution using eig(K,M)
• Sorting natural frequencies
• Displaying numerical results
• Plotting:
Natural frequency vs Mode number
Time response vibration curve
The built-in eigenvalue solver is used for accurate computation.
→ Results
The computational analysis yields:
Natural Frequencies:
• ω₁ ≈ 21.73 rad/s
• ω₂ ≈ 45.98 rad/s
In Hz:
• f₁ ≈ 3.46 Hz
• f₂ ≈ 7.32 Hz
Graphical Output
The program generates:
• Natural Frequency vs Mode Number graph
• Smooth sinusoidal vibration response curve
• Mode shape representation
These graphs help visualize dynamic characteristics of the system.

APPLICATION:-
Natural frequency estimation is essential in:
• Vehicle suspension design
• Machine foundation analysis
• Rotor critical speed determination
• Bridge vibration analysis
• Aerospace structural design
• Earthquake-resistant structures
Avoiding resonance ensures safety, reliability, and structural stability.
This project highlights the importance of matrix methods and computational tools in modern mechanical engineering vibration analysis.
How to Run the Project
•	Open MATLAB
•	Copy the provided .m file
•	Run the script	
Observe: • Natural frequencies in Command Window
• Frequency vs Mode graph
• Time response vibration curve

Author
Harsh Makwana
3rd Year Mechanical Engineering Student
Computational Vibration Analysis Project

Project Summary
This project successfully demonstrates how natural frequencies of a spring–mass system can be determined using matrix eigenvalue methods in MATLAB.
It reinforces the importance of vibration analysis, computational modeling, and eigenvalue techniques in modern engineering system design.

