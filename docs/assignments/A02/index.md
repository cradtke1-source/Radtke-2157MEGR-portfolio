# A2 – Truss Stress Analysis

## Step 1 Truss Geometry

For Assignment 2 I was assigned this set of points and connections and tasked with making a truss for them.

<img width="317" height="215" alt="image" src="https://github.com/user-attachments/assets/a51dfc2d-5538-4807-b10e-f7766c1099c5" />

P was set, by me, to 25 kN. a = .4 m, b = .3 m. Point A is a pin and point B is a roller. My first task was to draw a simple truss geometry, so I created a 7 member truss connecting all points and added an extra point "E" inbetween the pin and roller connection. With this diagram I began drawing up FBDs of the whole structure, and of the points. To solve the FBDs I first took a moment of B to find Ay then used trigonometry to find the angles present in the truss. This allowed me to solve the FBDs of the points and gave me all the member forces.
<img width="917" height="922" alt="image" src="https://github.com/user-attachments/assets/c9b4fcc6-f290-4365-84b7-7ef14b156fce" />



I determined that my largest force is 41.734 kN and to find the cross sectional area of the beam I needed to use my known factors, the max force, saftey factor, density of steel and yield strength of steel (317 mpa) to find  the cross section and approximate weight of the truss.

<img width="922" height="712" alt="image" src="https://github.com/user-attachments/assets/52200c0f-ac56-4b5e-88a2-60ec71eb9ee8" />

## Step 2 Pin Calculations

To find the area of a pin in a single shear I needed to use my known factors, the governing force, saftey factor, density of tool steel and the given shear strength to find the cross section and approximate weight of the pins. To help me with this I made an FBD of pin D and combined the vectors of the forces P and DC into F1. Because the sum of forces equals 0 and F1=FA I was able to turn 4 forces into two. Somewhere along the calculations I used the saftey factor twice and that had a cascading affect that would change my area and weight calculations. This caused me to panic and made me assume that my problem was the single shear and so I did double shear even though the instructions said not to and that further corrupted the calculations. Only when working on the CAD models did I realize my mistake and had to go back and erase all my work.

<img width="997" height="527" alt="image" src="https://github.com/user-attachments/assets/bb868ca7-6395-499f-b4b4-239d58fbf3a2" />

<img width="897" height="422" alt="image" src="https://github.com/user-attachments/assets/0737591f-4b3e-477d-b29a-d86b566d31f0" />


## Step 3 CAD Process and Showcase
<img width="1917" height="1091" alt="pin radius" src="https://github.com/user-attachments/assets/d943eb1f-8222-432a-b5c7-36108ddb5295" />
<img width="1917" height="1142" alt="pin length" src="https://github.com/user-attachments/assets/d01f71c9-1d29-4465-98ab-3186e1e75311" />
<img width="1905" height="1137" alt="image" src="https://github.com/user-attachments/assets/1527220b-8987-481c-9b13-becfccd4dc7f" />
<img width="595" height="446" alt="image" src="https://github.com/user-attachments/assets/59f40e96-6e1c-4727-996a-2cdcb6a28ffd" />
For me modeling the truss was the most difficult part, so I started with the pin. Using the area I could find the radius then the diameter and using the square fo the area of the struss cross section I found the length. Combining all of this together and doing the mass simulation resulted in a percent difference of 14.67%. this could be atrributed to how fast and loose I played it with sig figs, or my misunderstanding of the material selection (type A2 tool steel in solidworks).
<img width="1912" height="1096" alt="truss dimensions" src="https://github.com/user-attachments/assets/41ef51e3-16e2-4730-ba73-5a9246aab770" />
<img width="1907" height="1140" alt="truss weight" src="https://github.com/user-attachments/assets/55489c27-fa00-4e37-8277-acf7d1fd24c7" />








## Step 4 Communicate Lesson

In this assignment I learned that thinking ahead is very important for making things on time. I did not start to install Solidworks until saturday and had connectivity and downloading issuses that stopped me from working on the models up until sunday. I also learned pencil and paper is not an ideal medium for working in my case because I have very bad handwriting due to dexterity issues, in the future I want to get either a tablet or type up my work for legibility of future assignments. The problem is non keyboard symbols and diagrams still have to be drawn and scanned. In total I spent about 10 hours on this project.
