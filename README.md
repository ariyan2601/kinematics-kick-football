Independent Biomechanics Project by Ariyan Saha

Overview
This project analyzes the 2D trajectory, velocity, and acceleration of two football free kicks using video-based motion tracking. Frame-by-frame coordinates were extracted and processed using numerical differentiation with smoothing filters.

Contents
/report – Full analysis
/data – Raw coordinate tables, source video
/graphs – Trajectory, velocity, acceleration plots


Methodology
Frame extraction and tracking
Position → velocity → acceleration derivation
Moving average smoothing
Horizontal vs vertical component analysis
Basic aerodynamic interpretation (Magnus effect)

Key Findings
The analysis successfully isolated the physical differences in impulse required for each shot, while also demonstrating the critical importance of systematic error analysis in sports biomechanics.
Parameter,Curled Kick (Kick A),Knuckle Ball (Kick B),Interpretation
Max Raw Velocity (Vmax​),1.36 m/s (Unreliable),32.137 m/s,Kick B confirms professional launch speed.
Max Raw Acceleration (Amax​),71.66 m/s2,1477.25 m/s2,Knuckle Ball requires 20x higher instantaneous Impulse.
Launch Angle (θ),45.1∘ (Theoretical Range),5.19∘,Confirms flat trajectory necessary to eliminate spin (Magnus effect).
Conclusion,"Systematic Error Analysis. Data used to verify method, not velocity.",Validated Kinematics. Confirms high impulse and low angle required for minimal spin.,


Skills Used
Biomechanics • Video Tracking • Data Processing • Excel • Kinematics • Report Writing
