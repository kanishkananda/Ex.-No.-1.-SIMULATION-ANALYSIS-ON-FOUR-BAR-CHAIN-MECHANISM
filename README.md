# Ex. No.  - SIMULATION ANALYSIS ON FOUR BAR CHAIN MECHANISM

## DATE: 10/3/26

## AIM:

###   To determine & simulate the displacement, velocity & acceleration analysis for the given four bar chain mechanism. 

###   In a four bar chain ABCD, AD is fixed and is 120 mm long. The crank AB is 30 mm long and rotates at 100 rpm clockwise, while the link CD = 60mm oscillates about D. BC and AD are of equal lengths. ∟BAD = 600.

![image](https://github.com/Sellakumar1987/Ex.-No.-1.-SIMULATION-ANALYSIS-ON-FOUR-BAR-CHAIN-MECHANISM/assets/113594316/03952954-387e-4fd3-a1a0-a8dd4b82ae07)

## REQUIREMENTS:
###  ●	Mech Analyzer software.
###  ●	Processor: Minimum 1.5 GHz
###  ●	RAM: Minimum 512 MB
###  ●	Operating System: Windows XP, Windows Vista, Windows 7, Windows 8 or higher.
###  ●	Dependencies: Microsoft .Net 2.0 framework
###  ●	Mini Drafter.
###  ●	Geometry instruments.

## PROCEDURE:
###  Step 1: Draw the mechanism

Draw the four-bar linkage ABCD to scale.

Mark all given dimensions:

AD = 120 mm (fixed link)

AB = 30 mm (crank)

CD = 60 mm (oscillating link)

BC = unknown (equal to AD, so BC = 120 mm)

Mark the fixed pivot points A and D.

### Step 2: Position analysis (Displacement)

Assign the input angle: ∠BAD = 60° (or variable if performing simulation).

Use vector loop method or graphical construction to find coordinates of B and C:

Vector equation: AB + BC = CD + DA

Solve for unknown link angles: ∠ABC, ∠BCD.

Plot the mechanism in different crank positions to get displacement of B and C.

### Step 3: Velocity analysis

Angular velocity of crank AB
𝜔AB=2𝜋𝑁/60
𝜔AB=2𝜋×100/60
𝜔AB=10.47 rad/s
This value of VBA is used to decide the scale for the velocity diagram
velocity at point B
Step 2: Velocity of point B
𝑉𝐵=𝜔𝐴𝐵×𝐴𝐵
VB=10.47×0.03
𝑉𝐵=0.314 m/s

### Step 4: Acceleration analysis

Apply relative acceleration method:
 Acceleration of B: 𝑎𝐵=𝛼𝐴𝐵×𝐴𝐵−𝜔2𝐴𝐵×AB
 Acceleration of C: 𝑎𝐶=𝑎𝐵+𝑎𝐶/𝐵
​Resolve accelerations into tangential and normal components.
Calculate magnitude and direction of accelerations for each link.

![image](https://github.com/Sellakumar1987/Ex.-No.-1.-SIMULATION-ANALYSIS-ON-FOUR-BAR-CHAIN-MECHANISM/assets/113594316/76094ae8-a8af-48f3-b2c4-472ab800cc8e)

![image](https://github.com/Sellakumar1987/Ex.-No.-1.-SIMULATION-ANALYSIS-ON-FOUR-BAR-CHAIN-MECHANISM/assets/113594316/cb44fabe-6e16-4550-a2ec-4ee0f4cb6774)

###   1. First measure cd from velocity diagram  
###   2. Now, Calculate VCd using the scale of the diagram 
###   3. Finally, calculate ωcd from the relation v = rω 
###   Thus, link CD revolves with ωcd = 4 rad/s (clockwise about D) 



## Output:
<img width="1139" height="803" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/5c23d718-1227-4f4c-9dda-60eaced4f1d5" />
<img width="1148" height="773" alt="Screenshot (84)" src="https://github.com/user-attachments/assets/f81ecc89-13f5-4b47-aca8-bf76f89bdad5" />
<img width="1135" height="796" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/9eb368ff-e37c-47f9-a76b-8a134e6c5046" />

<img width="1147" height="801" alt="image" src="https://github.com/user-attachments/assets/3d4d2b0c-fd39-499c-b486-7bee2fe27680" />
<img width="1141" height="752" alt="image" src="https://github.com/user-attachments/assets/a0f0d49b-ce12-4aa3-b217-249ec3e7d7ae" />

<img width="1146" height="752" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/a398f84a-fb5a-4212-a94d-409131d8dd12" />
<img width="1142" height="803" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/a8a7b9ea-0a01-400d-8c73-863966b84205" />




### Name:KANISHKA N
### Register Number: 212225230127

## RESULT:
 ### Thus the displacement & velocity analysis for the given four bar chain mechanism is simulated.
