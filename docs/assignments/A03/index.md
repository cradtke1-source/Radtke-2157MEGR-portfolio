# A3 – FEA and parametric

## Step 1
I was tasked with making a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. I picked a diameter of .25 inches for my bar and found the resulting area. I could then use this when plugged into the direct tension elongation equation from Machinery's Handbook.

<img width="1547" height="930" alt="sketch" src="https://github.com/user-attachments/assets/98eaaa53-df6b-4da8-9404-04439f223148" />

I would then sketch and extrude the shape (this is after I went back because I did not record all steps chronologically)

<img width="932" height="426" alt="parametric" src="https://github.com/user-attachments/assets/6941897b-b3ea-4c47-b03e-3cd0703d1178" />

Then to make sure the shape was parametric I recorded all values and equations.
## Step 2
For the FEA simulation, I chose a fixed geometry at one end of my bar and applied the distributed load of 400 lB/ft to the end of the bar.

<img width="1912" height="995" alt="vonmises in imperial" src="https://github.com/user-attachments/assets/fa58617a-f8e9-4e3d-9511-2a183e51905d" />

Running the simulation gave me this Von Mises curve

<img width="1917" height="971" alt="deflection in imperial" src="https://github.com/user-attachments/assets/1c569a13-b69d-4aa5-a14a-810f0de6e4b4" />



## Step 3


## Step 4
This took me about 4 straight houts to complete. The only mistake I made was initially have my FEA readout in metric and not catching it, which made me panic and redo my bar.

