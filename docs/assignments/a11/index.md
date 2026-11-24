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

<img width="655" height="1066" alt="A11_Owen3 (1)" src="https://github.com/user-attachments/assets/ca52b074-b85b-4b2b-a905-8e4d7964e1c4" />


*Figure 4. Fine-mesh stress at the critical cross-section and along the rail. The dashed line marks the 43.09 MPa allowable stress.*



## Bearing mount
In order to design a bearing mount with an RC3 fit I needed to look through the machinery's handbook. I listed my known outer diameter and needed tolerances for the design. From here I drew the FBD and proceeded to solve for the thickness and diameter of the inner wall using torque analysis equations. 

 
## Clearances

### RC3 fit 

| Feature | Size (in) | Limits (in) |
|---|---|---|
| Bore (hole) | 0.4375 | +0.0007 / −0.0000 → 0.4375 to 0.4382 |
| Journal (shaft) | 0.4375 | −0.0006 / −0.0010 → 0.4365 to 0.4369 |
| Clearance | n/a | 0.0006 min, 0.0017 max |

### Bolt clearance holes (1/4-20)

| Close fit | Normal fit |
|---|---|
| 0.266 in (17/64) | 0.281 in (9/32) |
| 0.2570 in (F) | 0.2656 in (17/64) |

0.281 selected

## Justification of dimensions

| Dimension | Value | Justification |
|---|---|---|
| Journal Ø | 0.4375 in | Below the Acme minor diameter (about 0.480 in), so the thread runs out at a shoulder. Within the 0.40–0.71 in RC3 size range. |
| Bore depth | 1.00 in | 0.75 in of bearing contact plus 0.25 in end gap for thermal growth and oil. |
| Bearing length | 0.75 in | L/D ≈ 1.7, inside the usual 1–2 range. Resists tilt without edge loading. |
| Shoulder stand-off | 0.125 in | Keeps the end floating. Acts as a safety stop if the coupling slips. |
| Boss Ø | 1.00 in | Leaves a 0.28 in wall around the bore. |
| Boss height | 1.25 in | 1.00 in bore plus 0.25 in floor. |
| Base plate | 3.00 × 2.00 × 0.375 in | 2.00 in covers both crossbar rails. 0.50 in edge distance on all bolt holes. |
| Bolt pattern | 2.000 × 1.000 in | 1.000 in lands bolts on the two slot centerlines. 2.000 in keeps bolt heads clear of the boss. |
| Axis location | Crossbar centerline | Midway between slot rows. Slot nuts slide, so the block can be aligned to the coupling. |
| Bolts | 1/4-20 × 3/4 SHCS | Pass the slot lip and fully engage the slot nut. |

<img width="896" height="910" alt="image" src="https://github.com/user-attachments/assets/28e8627f-09da-4dd7-b774-265455f7873d" />

## Tabulating costs
| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
|---|---|---|---|---|---|
| 1 | 2 | Aluminum Frame Rail (4601N78) | $18.72 | $37.44 | [McMaster-Carr](https://www.mcmaster.com/4601N78) |
| 2 | 2 | Aluminum Frame Rail (4601N73) | $12.01 | $24.02 | [McMaster-Carr](https://www.mcmaster.com/4601N73) |
| 3 | 2 | 5/8"-8 Carbon Steel Acme Lead Screw, 24" (98935A914) | $9.79 | $19.58 | [McMaster-Carr](https://www.mcmaster.com/98935A914) |
| 4 | 2 | 5/8"-8 Acme Flange Nut, 932 Bearing Bronze (95120A119) | $138.20 | $276.40 | [McMaster-Carr](https://www.mcmaster.com/95120A119) |
| 1 | 1 | Stepper motor (6627T671) | $210.56 | $210.56 | [McMaster-Carr] https://www.mcmaster.com/6627T671/ |
| 1 | 2 | Flexible shaft coupling( 6259K35) | $413.44 | $413.44 | https://www.mcmaster.com/6259K35/ |
| | | Labor Cost at 35/hr | | $420.00 |
| | | **Total Cost** | | **$1401.44** | |

## Communicate
We collectively worked 12 hours on this project. The most difficult part about working on this project was when multipart questions were split among two people. The frame FEA for example was worked on and developed independently by two people. This resulted in frames of two different constructions and the need to realign calculations in favor of one or the others model. We worked this out by deferring responibility to the prson more familiar with the part run tests to allow a smoother and quicker workflow.
