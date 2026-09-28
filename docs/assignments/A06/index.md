# A6 – [Topic]

## Modeling
<img width="1302" height="927" alt="image" src="https://github.com/user-attachments/assets/514cd217-6189-4bb7-a2b4-cc0f82c92617" />

I decided to use the stiffness model for my parametric model. I set the unit system to IPS (inches, pounds, seconds) and applied 6061-T4 (SS) aluminum as the material. I then started a sketch on the Front Plane and drew the bracket's cross-section, which is a rectangular bar with two thin tabs across the top and a stem and cylinder below it. I placed the origin at the center of the cylinder and used it as the reference for the other dimensions. I dimensioned the sketch with an overall width of 3.07 in, an inner cavity width of 2.94 in, an overall bar height of 1.11 in, a 0.50 in slot height, and 0.03 in tab thickness. The left tab measures 1.06 in and the right tab 0.99 in. The stem is 1.00 in tall, and the cylinder has a 1.10 in diameter. I extruded the profile 0.90 in using Boss-Extrude features
## Parametric equations
<img width="936" height="357" alt="image" src="https://github.com/user-attachments/assets/c2427c26-af51-495e-a39f-cdae7efeec3a" />

To make the model parametric, I created global variables under Tools > Equations for the key dimensions and linked the sketch and extrude dimensions to them. This lets me change the bracket's size by editing a few values instead of redoing each sketch.
## Drawing
<img width="1197" height="920" alt="image" src="https://github.com/user-attachments/assets/d690f3b6-3f3b-4350-890d-1fb85957e17c" />
 
To make sure the part met its specified tolerances, I went back through the model and added the correct tolerances and significant figures to each feature.  SolidWorks can be picky about how tolerances display, so I had to select each dimension and set its tolerance type and precision in the Dimension PropertyManager. The drawing gives an isometric view along with the top, front, and right-side views in third angle projection.



## Communicate
I spent 4 hours making this. Fot the tolerences of my parts is did loose and ointermediate tolerances for most of the faces that interact with the T bar. This is so sliding the bar in and out is easy. If I did tight tolerances the cost of manufacturing would be much higher ansd the fit might not be so easy to use if it's too snug.
Download [[bracketpara.zip](https://github.com/user-attachments/files/32715571/bracketpara.zip)]

