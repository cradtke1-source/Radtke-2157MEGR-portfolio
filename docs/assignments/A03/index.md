# A3 – FEA and parametric

## Step 1
I was tasked with making a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. I picked a diameter of .25 inches for my bar and found the resulting area. I could then use this when plugged into the direct tension elongation equation from Machinery's Handbook.

<img width="777" height="557" alt="image" src="https://github.com/user-attachments/assets/e8a56adf-082c-4f0a-8432-c5cfe48271a8" />

<img width="1547" height="930" alt="sketch" src="https://github.com/user-attachments/assets/98eaaa53-df6b-4da8-9404-04439f223148" />

I would then sketch and extrude the shape (this is after I went back because I did not record all steps chronologically)

<img width="932" height="426" alt="parametric" src="https://github.com/user-attachments/assets/6941897b-b3ea-4c47-b03e-3cd0703d1178" />

Then to make sure the shape was parametric I recorded all values and equations.
## Step 2
For the FEA simulation, I chose a fixed geometry at one end of my bar and applied the distributed load of 400 lB/ft to the end of the bar.

<img width="1912" height="995" alt="vonmises in imperial" src="https://github.com/user-attachments/assets/fa58617a-f8e9-4e3d-9511-2a183e51905d" />

Running the simulation gave me this Von Mises curve the yield strength of the beam was 8709 psi, which would mean a safety factor of 4.6 was applied to the bar. This was lower that the 40 ksi parameter.

<img width="1917" height="971" alt="deflection in imperial" src="https://github.com/user-attachments/assets/1c569a13-b69d-4aa5-a14a-810f0de6e4b4" />

Next the deflection resulted in a value of 0.008970 inches which was under the max of 0.009 inches.



## Step 3
<img width="766" height="255" alt="image" src="https://github.com/user-attachments/assets/b395fa14-8f05-4bea-a080-1cb3a08b587e" />

I got a sub 1% difference which is very good. I personally would pick the simulation calculations over my own any day. As to why I think they are so similar simple, uniform axial loading, a constant cross-section and similar underlying physics are why the calculations might be that way.

<img width="716" height="331" alt="image" src="https://github.com/user-attachments/assets/26e149a4-1304-4341-94a0-be892007a445" />

For the hole question I got a new psi which satisfies the 40000 psi maximum and a saftey factor of 2.1.
## Step 4
This took me about 4 straight houts to complete. The only mistake I made was initially have my FEA readout in metric and not catching it, which made me panic and redo my bar.

