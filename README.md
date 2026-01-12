# Lift-Platform-Challenge

<h2>The Goal</h2>

The Goal of this Project was to lift up a weight of 3-5lbs up 4 inches only powered by a motor from below with a team of three to 4 as listed in the [project rules](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Project%20Rules.pdf). 

But a quick overview includes:
- The device was required to fit within a cube with an 8x8x8 inch volume at the start
- It would need to lift a payload of at least 3.1lb, preferably 5lb, up 4 inches with a single DC motor and battery as the power source.
- The system was to be self-standing
- operate without stored mechanical energy
- complete lifting and resetting operations under 4 minutes

<h2>The process</h2>
<h3>The Beginning</h3>
We first began by brainstorming 3 different designs based off of current designs out there and the three that we came up with were a Rack Lift a Scissor Lift and a Screw Lift. We talked about the different designs and ended up going with the Scissor lift as described in [Design Update 1](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Design%20update%201/Design%20Update%201.pdf). We then thought about how to produce the design while still following the project rules. For each of the designs we calculate the required gear torque needed to lift the weight and the efficiency from a gear train to determine the best build where we came up with a Scissor lift design and our initial sketch is shown below.

<n><img width="234" height="413" alt="Picture3" src="https://github.com/user-attachments/assets/b58bd99b-6bcf-42b0-9bd1-20dcae9b063e" />


<h3>The Calculations and Further design</h3>

We wanted the torque of the motor be amplified by the gear train to provied a pulley system which rotates a spool pulling the bottom of the scissor lift.

When we first calculated the gear ratios for the scissor lift we did them completely wrong which messed up our final design but the gears that we used in our final design include which would probably still give enough torque to the scissor lift

- 3 12 tooth Gears
- 1 24 tooth Gear
- 1 36 tooth Gear
- 1 60 tooth Gear

From computing the gear ratios we can compute static analysis on the gear ratios shafts and the body of our scissor lift as show in [Design Update 2](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Design%20update%202/Design%20Update%202.pdf) using super position. We can also calculate many other factors that will help our design including:

- Deflection Analysis
- Stiffness
- Static Ductile Failiure

We also computed more calculations in [Design update 3](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Design%20update%203/Design%20Update%203.pdf) including:

- Stress Concentration and Stress intensity Factors
- Identification of Simple, Reversed, Fluctuating, or Combined Loading
- Failiure Criteria, Constant Lift Curves
- Identification of the highest loaded bolt joing with different analyses including
  - Tension
  - Shear
  - Failiure

 <h3>The Building</h3>

 When building the scissor lift we bought all of our parts based off of their quality and being cheap as shown in the [Bill of Materials](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Scissor%20Lift%20BOM.xlsx) We 3D printed all of the shafts and the main body for the gear train and most of the scissor lift body was made out of Aluminum for the strength and cheapness. The cad and the main body of the scissor lift is shown below.
 
<img width="218" height="375" alt="cad" src="https://github.com/user-attachments/assets/43edd0e5-8d49-4546-989a-35b072edce60" />
<img width="297" height="374" alt="main" src="https://github.com/user-attachments/assets/1ce610db-b628-438b-86e5-19505a03d4df" />

for our electric design we followed the design shown in the [project rules](https://github.com/IamWright1/Lift-Platform-Challenge/blob/main/Project%20Rules.pdf) which was:

<img width="235" height="365" alt="Screenshot 2026-01-11 193535" src="https://github.com/user-attachments/assets/2385bf48-9700-468d-9b61-88f8a2c22019" />

Where our final circuit looked like [this](https://github.com/user-attachments/assets/54d99665-ffc7-4d2d-b5aa-ace37593523f).

<h2>Reflection</h2>

In the end I learned how to do mechanical analysis on many parts including the shafts in the gear train and bolts mounting the lift. I further developed my skills in SolidWorks when designing the whole gear train and developed my skills with 3D printing using Bambu X1C, Prusa Mk4, and Flash Forge 5m.



