# A5 – Bracket
My objective was to.
Conduct stress analysis to determine appropriate dimensions for structural features.

Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.\

Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.

Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.

Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.

Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.

Reflect on and document key engineering lessons learned throughout the process.
## Stress
I chose to work with aluminium and started with part A I drew out the fbd  aswell as writng out the constant knowns and assumptions for the whole design. To determine the required size based on bending stress I modeled it as a canteleiver beam.

<img width="497" height="635" alt="image" src="https://github.com/user-attachments/assets/f71a6c2f-7e27-43d9-8cb5-e8595ce05e28" />

For parts B-E I repeated the same process.

<img width="497" height="635" alt="image" src="https://github.com/user-attachments/assets/24f1c01a-692f-4d04-8258-b63e6488f0b7" />


<img width="497" height="640" alt="image" src="https://github.com/user-attachments/assets/15a6522b-b788-426f-b1e5-0d00f7cbb70d" />


<img width="496" height="645" alt="image" src="https://github.com/user-attachments/assets/b169561c-2c81-464d-8d97-d0e7d4993c3d" />

## Stiffness
Using the deflection reqirements for A-E I got these seperate measurments of each part.

<img width="497" height="675" alt="image" src="https://github.com/user-attachments/assets/7f787539-3171-4ec0-aec0-66c895eaebcb" />


## Multiview
I created a multiview sketch of the bracket using the dimensions determined from the stress and stiffness analysis. The drawing shows the overall geometry and how the calculated feature sizes fit around the required T-beam dimensions. This allowed me to directly compare the stress-based and stiffness-based designs before selecting the governing dimensions for the final bracket.

<img width="506" height="651" alt="image" src="https://github.com/user-attachments/assets/960172bd-38ae-4d4e-808f-4d5a58adb2f4" />


## Lessons
Governing Failure Mode - Stress governed for every part, and it ususally wasnt close except for part E. 
Error propagation - The reaction forces from part C affect parts D and E, because the bracket was treated as symmetrical, the load was split between both ends. Bad math in C would cascade into affecting D and E.
Assumption Sensitivity - I assumed aluminium was the correct choice. If I had choses a different material every single calculation would be diffrent because the modulus of elasticity was relevant to figurung out the length for figure A which has a cascading affect on the dimesions of every other part.
