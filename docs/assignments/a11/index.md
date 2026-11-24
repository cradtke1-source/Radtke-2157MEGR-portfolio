# A11 – Motor Selection

## Objective


## Analyze


## 4. Frame Connector Analysis

### Frame Design

The frame retains two uprights, one top rail, a mid-height rail, and a moving crosshead. The clear span of the 40 Series top rail is 304.8 mm. Each lead screw transfers 1,000 N at the 2 kN test load. The analysis assumes 5.908 N·m per motor and a 35 mm screw offset. The required safety factor is 4.

<img width="1567" height="503" alt="A11_Owen4" src="https://github.com/user-attachments/assets/56b3bcbd-5a73-4dd9-91a1-8bf59545d466" />


*Figure 1. Onshape model showing the top rail, corner gussets, and moving crosshead.*

![Onshape model](https://cad.onshape.com/documents/83e583c401f83cf1aef066d5/w/961b5aa68a69216805b43551/e/13353e8c436f19b80af2834e?renderMode=0&uiState=6b04d176934955b4bf799132) | [Download STEP](https://drive.google.com/file/d/1LDdD4cBsOxAlF0AWm4i417Tt2S1ZpgyX/view?usp=sharing)

### Knowns, Unknowns, and Free-Body Diagram

The unknowns are the joint reactions and the shear, pull-out, and slip capacity of the connector hardware. Symmetry gives a vertical reaction of 1,000 N at each end. Using a reaction spacing of 344.8 mm, the two motor torques produce a transverse reaction of 34.27 N at each end, acting in opposite directions. The 35 mm offset of each screw load produces a roll moment of 35 N·m at each end.

<img width="2160" height="2880" alt="A11_Owen1" src="https://github.com/user-attachments/assets/71075666-36cd-43ed-919e-f3f3aa4c2666" />


*Figure 2. Top-rail free-body diagram showing the vertical loads, motor torques, and transverse reactions.*

### Connector Selection

One 80/20 40-4336 gusset is proposed at each top corner. It uses M8 hardware in the existing T-slots. With an assumed 18 mm contact lever arm and two bolts sharing the load, the preliminary demand per bolt is 0.97 kN in pull-out and 0.50 kN in shear. The shear estimate is based on the vertical reaction.

At a safety factor of 4, the required capacities are 3.89 kN in pull-out and approximately 2.00 kN in shear per bolt. The combined capacity and resistance to slipping along the upright T-slot still need verification.

<img width="2160" height="2880" alt="A11_Owen2" src="https://github.com/user-attachments/assets/86c4a9d9-23b8-4f2e-8fcf-ececdff7f82d" />


*Figure 3. Hand calculations for the joint reactions, preliminary connector loads, and top-rail safety factor.*

### Top-Rail Stress Check

The fine-mesh results show a peak von Mises stress of approximately 39 MPa near the left end of the rail. Using the assumed yield strength of 172.37 MPa, the allowable stress for a safety factor of 4 is 43.09 MPa. The resulting top-rail safety factor is approximately 4.42, which meets the requirement for the modeled load case.

(single-rail-assets/A11_Owen4.jpg)

*Figure 4. Fine-mesh stress at the critical cross-section and along the rail. The dashed line marks the 43.09 MPa allowable stress.*



## Decide


## Communicate
