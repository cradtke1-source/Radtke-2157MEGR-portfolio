# A10 – Lead Screw Translating System

## Lead screw design - Cooper Radtke
Our goal is to design and build a mechanically driven tensile tester capable of applying up to 2 kN axial tensile load with a controllable crosshead speed from 1 to 50 mm/min. This is to be done with 2 screws that are at minimum 18 inches long. All calculations must use a safety factor of 4. To design the lead screw I first needed to find diameter. I compiled knowns and unknowns, drew an FBD and solved algebraically and numerically to get a diameter of .38 inches.


<img width="601" height="690" alt="image" src="https://github.com/user-attachments/assets/758ca33d-0152-41e9-a00a-7f78156a0bb4" />

I repeated this process twice for the rotational speed and torque and got a range of .032 - 1.59 rpm and 5908 Nmm respectively.


<img width="376" height="500" alt="image" src="https://github.com/user-attachments/assets/5c7bcae4-fdc1-427b-a7c5-6964d2355347" />

## Analyze
The lead Screw was chosen to be 5/8 -8 Carbon steel lead screw with the part number 989335A914. For the nut, it would require the corresponding nut with the same specifications; the material is already chosen to be bronze, with all further testing to ensure that the given thread size for the bolt won’t fail under the given load. The image below shows the part on McMaster-Carr where the design specifications are given along with the 3D part model. The Thread type is Acme; the inner diameter to the base of the threads is 5/8 in (0.625 in); the total height is 1.25 in; the pitch is 0.125 in; the thread height is half the pitch; and the other measurements are unnecessary for the current calculations. 
Here is the link to the website below: https://www.mcmaster.com/products/acme-lead-screws/nut-type~externally-threaded/nut-type~flange/material~bronze-1/material~932-bearing-bronze/thread-size~5-8-8/


On the website above, the Yield strength, a necessary upper limit to know, was not given and therefore had to be found on an alternative website. Also important to note as stated on the website above, there are two different types of bronze metals. Doing a little research at concast.com, 932 would function better, as it is the workhorse of industry. While 673 has better stress resistance, 932 self-lubricates, which is important when running up and down the leadscrew, reducing wear. The Yield strength for this specific alloy is 20 ksi.
The link to the PDF below is given here: https://morganbronze.com/wp-content/uploads/c932_bearing_bronze.pdf










The given Knowns are a safety factor of 4, an allowed stress limit of 20 psi, and a pitch of 0.125 in; the object itself and material is a 5/8 – 8 932 bronze lead screw nut; the force is ½ the given load, and the given load for the assembly as a whole is 2kN. However, all the measurements are already in the US Customary System, so 2kN was converted to 449.62 lbf. The unknown value is a ratio; rather, to ensure that the stress experienced by the nut didn’t exceed the given material, the stress of the bearing nut multiplied by the safety factor, over the allowable stress, has to be less than 1. Using the given equations, the real stress was calculated to 2747.86 lbf*in, well within the stress allow. 






	DESIGN A CROSSHEAD

In this section, we are tasked with designing a crosshead using simple beam design to calculate the necessary dimensions using the stress and vertical deflection equations. The total load is the same, and Aluminum was chosen as the material because it’s relatively easy to mill and affordable.
The first crosshead dimensional design is based on stress analysis; the base is 1.65 inches, as the diameter of the nut flange is 1.5, and this leaves 75 thou of clearance on either side. As for the length, none of the previous calculations answered, so the length was decided to be half the length of the Lead screws on either side, or 12 inches. The load multiplied by the safety factor is force P, and the height is the dimension being solved for. And additional documents were used in order to find the Yield strength of aluminum, which is 40 ksi and is listed below.
 For the stress equation, the height was derived to be 1.4 inches.






The second crosshead design is based on the max deflection, which is 0.01mm with a modulus of elasticity of 10,000 ksi, found with an outside source listed at the bottom. All other values remain the same. As the max deflection was given in mm, the deflection was converted to the U.S. customary system of measurement. The deflection in inches was 0.003937 in.
The height was derived to be 2.702 in.





Before the design phase, using the Master thesis provided as a reference in the resources section of this assignment, I roughly used this image for a design concept before creating the Multiview drawing.


In the instructions, it asks for a Multiview sketch to be generated; however, it doesn’t expressly ask for a 3D model to be created, so instead a handmade design was created on paper. However, it’s missing any tolerance, and any holes are made exactly to the size of the 5/8 - 8 nut. All important measurements are included, and front, side, and top views are included along with an orthogonal view, along with units and the Part name. It’s a simple beam with an extra 1.5-inch section at the top to possibly create an insert, depending on the nature of the next assignment. The curved edges are to reduce stress, as was the case in the Bracket design in a previous assignment. The height chosen was based on the vertical deflection, as it met both stress and deflection requirements.
 



## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate

