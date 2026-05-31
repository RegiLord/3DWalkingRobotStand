### 3DWalkingRobotStand

&emsp;A 3D fusion 360 project consisting in STL files of the pieces and f3d of the entire project.

<a href="https://a360.co/3PSziw8">Link to fusion 360 project.</a>
### Description

&emsp;A stand containing a humanoid rig mechanical body with a horizontal crank that can be fully turned. Upon turning the handle the robot starts moving in place, turning it's hips, knees. It also has a minimal arm waving feature. The ideea of the rig is to be fully cusomizable, parts such as armor, boots, clothes, hands, heand can be modeled sepparately and attached to the rig using provided connectors in the project.

### Components

- Rig Support Stand x 1
- Crank Lever x 1
- Joint Legs (one left, one right) x 2
- Torso Rig x 1
- Arm Bars x 2
- Head Component x 1
- Coupler x 1
- Key Cog x 2
- Key x 2
- Cap x 17


## Rig Support Stand

&emsp;The support of the entire rig.

<img width="484" height="701" alt="image" src="https://github.com/user-attachments/assets/cdbf6673-568f-4df2-9e9a-b3879466fa71" />

## Crank Lever

&emsp;The moving mechanism of the robot, uses two cogs that will be described in Joint Legs as they are the same. This is the part that is meant to be rotated to start everything.

<img width="597" height="589" alt="image" src="https://github.com/user-attachments/assets/9e98f0b5-06e4-496d-900c-0efffa9ef727" />

## Joint Legs
&emsp; Will only show the right leg, the left one is the same but flipped. The legs are moved using a Jansen Mechanism Linkage.

<img width="970" height="475" alt="image" src="https://github.com/user-attachments/assets/ca919542-278d-42fb-a08c-5252d468d01a" /> 

&emsp; The cog is created using the fusion 360 add-in spur gear with the following parameters: Module = 1.5, Pressure Angle = 14.5, Root Fillet Radius = 0.5

<img width="626" height="588" alt="image" src="https://github.com/user-attachments/assets/c5adc3a9-fe11-4fe0-adb9-c4c392752bd2" />

## Torso Rig

&emsp; A simple triangle shaped rig for the torso parts and arms. To be mentioned that the torso is suspended compared to the legs.

<img width="497" height="786" alt="image" src="https://github.com/user-attachments/assets/530acd3d-2180-421c-8cfa-8968356704e7" />

## Arm Bars

&emsp; A simple bar meant to be attached to the torso, no fancy mechanism like in the legs.

<img width="923" height="588" alt="image" src="https://github.com/user-attachments/assets/f1c83618-2663-4ac2-9b38-9bb24ebe06f7" />

## Head Component

&emsp; A example part that could be used to decorate the rig.

<img width="679" height="624" alt="image" src="https://github.com/user-attachments/assets/cce19dfe-7d93-4d48-9e07-8db511932489" />

&emsp; At the bottom of the component is a part named Reverse Coupler that can be used with a Coupler (will be the next component) to attach anything anywhere on the rig. To make sure they are coupled we use the elasticity of the material as a basis.

<img width="518" height="508" alt="image" src="https://github.com/user-attachments/assets/e206f9f3-f99c-44ee-bdc0-9ca185dd1247" />\

## Coupler

&emsp; A piece that can be attached anywhere on the rig for coupling decorations.

<img width="433" height="507" alt="image" src="https://github.com/user-attachments/assets/3d6b5b52-6217-4c46-8c6a-65144e0b2818" />

## Key Cog and Key

&emsp; The core of the arm waving mechanism, we are presenting them together. The key is set into the support to ensure horizontal movement.

<img width="842" height="525" alt="image" src="https://github.com/user-attachments/assets/bf10f90a-f4a4-4df5-bd01-b4366d402cd8" />

<img width="592" height="478" alt="image" src="https://github.com/user-attachments/assets/81910d22-9c2f-4d95-b9cf-b05f8a75e88c" />

## Cap

&emsp; A simple component that ensures that some parts are fixed and will not fly off their pins.

<img width="711" height="576" alt="image" src="https://github.com/user-attachments/assets/ad33d687-49fe-4fe2-8a78-2020040d17e6" />

### Motion

&emsp; For motion there two main moving points, the arms and legs. Everything starts from the Crank Lever that rotates the cogs in the legs which then rotate the cogs in the arms. Unfortunately while the legs move pretty well the arms could definitely be worked on. As well that in fusion 360 the motion is not fully realized due mainly to unsufficient knowledge on my part.

&emsp; The legs utilize a Jansen Mechanism using Linkage bars to create a smooth movement, looking like the bending of a knee and hip. It is widely utilized in modern day robot.

&emsp; The arms are quite simple. They are push forward by the Key Cog and rely on gravity to fall back into position, the tolerance is bigger to allow these changes to happend.

### Software Used

&emsp;Fusion 360
