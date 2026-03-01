Independent Biomechanics Project by Ariyan Saha

Version1: Overview:
This project analyzes the 2D trajectory, velocity, and acceleration of two football free kicks using video-based motion tracking. Frame-by-frame coordinates were extracted and processed using numerical differentiation with smoothing filters.

Version2: 
Using OpenSim's Inverse kinematics model the 2D coordinates of the ball was used to generate the joint spaces of Hip flexion and knee angle. These values were used for static optimization to obtain the load exerted on the muscle due to the eccentric limb movement while kicking the ball

Contents:
/report – Full analysis
/data – Raw coordinate tables, Joint space tables, Muscle forces tables
/graphs – Trajectory, velocity, acceleration plots
/video- full videos that were analyzed

Methodology:
Frame extraction and tracking
Position → velocity → acceleration derivation
Moving average smoothing
Horizontal vs vertical component analysis
Basic aerodynamic interpretation (Magnus effect)
Biomechanical modeling using OpenSim
correlating the change of knee angle to impact motion
analyzing the force exerted on hamstrings during the impact phase and explaing the injury proneness of different motions

Key Findings:
The analysis successfully isolated the physical differences in impulse required for each shot, while also demonstrating the critical importance of systematic error analysis in sports biomechanics.
Isolated the Muscle forces exerted during the kcking motion and analyzed how high forces generated during eccentric shot taking can cause injury.

Skills Used
Biomechanics • Video Tracking and Kinematics • Data Processing • Excel • Report Writing • OpenSim 
