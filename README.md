# Razor MX650 Performance Upgrade

## Project Overview

I upgraded a Razor MX650 electric dirt bike to increase its power and overall performance. The project started as a motor and battery upgrade, but fitting the new components into the stock frame required several mechanical and electrical modifications. I also had to make changes to the drivetrain and brakes as I tested the bike and found problems with the original setup.

This project gave me experience working through real fitment, fabrication, drivetrain, electrical, and reliability problems instead of only replacing components.

## Main Upgrades

| System | Upgrade |
|---|---|
| Motor | 48 V, 1800 W brushless motor |
| Battery | 48 V, 20 Ah battery |
| Controller | 48 V multivariable controller |
| Brakes | Upgraded brake system with larger rotor |
| Drivetrain | 13T motor sprocket / 80T rear sprocket |
| Chain | Upgraded to a stronger chain after the smaller chain repeatedly failed |

## Motor Fitment and Fabrication

The upgraded motor did not fit directly into the stock MX650 frame, so I had to modify the setup to make it work.

I drilled clearance holes where needed so the motor could fit within the frame. The motor also came with a mounting plate that took up too much space, so I removed the plate and used the cylindrical motor body to get the clearance I needed.

This was one of the main fabrication parts of the project because I had to work around the limited space of the original frame while installing a much larger power system.

## Battery and Controller Installation

The 48 V 20 Ah battery was larger than the stock battery setup. To make room for it, I removed the upper stock battery holder and flattened/removed portions of the lower battery-holder walls that interfered with the new battery.

The new controller also did not have the correct connector for the battery. I soldered the correct connector onto the controller wiring so the battery and controller could connect properly.

## Drivetrain and Gearing

The upgraded motor came with different sprocket options, so gearing became an important part of getting the performance I wanted from the bike. Changing the motor sprocket changes the final drive ratio, which affects wheel torque, acceleration, and top speed.

### Initial 9T Sprocket Test

I initially ran a **9-tooth motor sprocket with the 80-tooth rear sprocket**. During the first riding test, my brother reported that the bike had more torque than necessary. The bike reached approximately **20 mph**, which was only about a **5 mph increase** over the roughly **15 mph stock top speed** I had before the upgrades.

That test showed me that simply having more motor power did not automatically give me the performance I wanted. The 9T sprocket provided a large gear reduction and strong wheel torque, but it limited the bike's top speed.

### Engineering Analysis and 13T Sprocket Selection

Instead of selecting another sprocket at random, I used the motor RPM, rear tire diameter, and sprocket ratio to estimate what gearing would put the bike near my target speed of about 30 mph.

For the final setup I used:

| Parameter | Value |
|---|---:|
| Motor speed | 4500 RPM |
| Motor sprocket | 13T |
| Rear sprocket | 80T |
| Rear tire diameter | 14 in |

The final drive ratio is:

**Final drive ratio = rear sprocket teeth / motor sprocket teeth**

**Final drive ratio = 80 / 13 = 6.15:1**

At 4500 motor RPM, the theoretical rear-wheel speed is:

**Wheel RPM = 4500 / 6.15 ≈ 731 RPM**

Using the 14-inch tire diameter, the calculated theoretical top speed was **30.5 mph**.

### Top Speed Calculation

![Top speed gear ratio calculation](Gear%20calculation%20for%20razor%20mx650%20by%20best-calculators.com.png)

The calculator gave a theoretical top speed of **30.5 mph** using 4500 RPM, a 14-inch tire diameter, and an overall ratio of 6.15:1.

### Testing and Validation

After installing the **13T motor sprocket**, I performed another speed test. The bike reached a measured top speed of **29.2 mph**, compared with the theoretical prediction of **30.5 mph**.

The measured result was about **4.3% lower than the theoretical value**. The theoretical calculation assumes ideal conditions and does not account for mechanical losses. On my bike, the original wheel bearings were somewhat worn, and I also noticed slight brake contact that added rolling resistance. These losses likely contributed to the difference between the calculated and measured speeds.

This gave me a useful theory-versus-test comparison: changing from the 9T to the calculated 13T sprocket moved the bike from approximately **20 mph to 29.2 mph**, while the calculated target was **30.5 mph**.

### Chain Failure and Upgrade

Another problem I found during testing was that the smaller chain I originally used kept breaking under the increased power of the 1800 W motor.

Instead of continuing to replace the same chain, I upgraded to a stronger chain that could better handle the load. This was a useful part of the project because the problem only became obvious after the bike was actually assembled and tested.

## Brake Upgrade

Since the upgraded bike was capable of higher performance than the stock MX650, I also upgraded the braking system.

I chose a larger brake rotor to increase braking torque. A larger rotor gives the caliper a larger effective radius to act on, so the same braking force can produce more torque at the wheel.

**Braking torque = braking force × effective rotor radius**

Upgrading the brakes was important because increasing the bike's power without improving its ability to stop would leave the overall system unbalanced.

## Problems I Had to Solve

Some of the main problems I worked through during the build were:

- Fitting a larger motor into the stock frame
- Creating enough clearance for the larger battery
- Modifying existing frame and mounting components
- Connecting the new battery and controller
- Testing the 9T gearing and identifying that it produced more torque than I wanted
- Calculating and selecting a 13T motor sprocket for a higher target speed
- Comparing theoretical top speed with the measured result
- Fixing repeated chain failures caused by the higher power
- Improving the brakes to match the increased performance

## What I Learned

The biggest thing I learned from this project was that changing one part of a mechanical system can affect several other parts of the design.

Increasing the motor power did not only require a new motor. It affected battery packaging, controller installation, gearing, chain loading, motor clearance, and braking. Some problems, especially the chain failures and the gearing characteristics, only showed up once I tested the finished bike.

The drivetrain was a good example of this. My initial 9T sprocket gave the bike strong torque but only about a 20 mph top speed. I used the drivetrain dimensions and motor speed to select a 13T sprocket, calculated a theoretical top speed of 30.5 mph, and then measured 29.2 mph during testing.

Working through those problems gave me experience modifying a real system, testing it, analyzing the results, and changing the design until the performance was closer to what I wanted.

## Skills Used

- Mechanical fabrication
- Electric drivetrain integration
- Component selection
- Gear-ratio and theoretical speed analysis
- Experimental testing and validation
- Brake-system design considerations
- Soldering and electrical connections
- Packaging and clearance problem solving
- Troubleshooting
- Hands-on prototyping and testing

## Project Videos

These videos document different stages of the build, from the initial electrical test through installation, first riding tests, drivetrain troubleshooting, and the completed bike.

### 1. Pre-Installation Electrical Test

[Watch the pre-installation electrical test](https://www.youtube.com/shorts/adXzm9Y-ZhQ)

After wiring the upgraded electrical components, I tested the system while it was still outside of the bike. I did this before installation to make sure the electrical system and motor were working correctly before mounting everything into the frame.

### 2. Components Installed in the Bike

[Watch the post-installation component test](https://www.youtube.com/shorts/GqMGUvGb6VI)

This video shows the electrical components after they were installed into the MX650 frame and how I packaged the system within the available space. I tested the components again after installation. At this point, the chain and final drivetrain setup had not yet been installed.

### 3. First Ride — 9T Sprocket Test

[Watch the first ride](https://www.youtube.com/shorts/6jxUeG4Upig)

This was the first riding test of the upgraded bike with the **9T motor sprocket**. My brother reported that the bike had a large amount of torque and that the braking performance needed improvement. The bike reached approximately **20 mph** with this gearing. This test helped show that I needed to change the gearing as well as improve the brakes.

### 4. Post-Repair Drivetrain and Stability Test

[Watch the post-repair riding test](https://www.youtube.com/shorts/k4TFucLBT2E)

This test was performed after fixing the chain/drivetrain setup. My brother rode and jumped the bike to put more load on the system and check that the chain remained engaged and that the installed components stayed secure during harder riding.

### 5. Completed Bike Overview

[Watch the completed MX650 overview](https://www.youtube.com/shorts/-amuYUIw6IQ)

This video is a cinematic overview of the completed bike and shows the overall appearance of the finished MX650 build.

## Future Improvements

Some things I would like to document or improve further include:

- Measure acceleration under controlled conditions
- Estimate wheel torque using the motor torque and gear ratio
- Measure battery range and power consumption
- Measure braking distance with the upgraded brake setup
- Improve wiring organization and component protection
- Design cleaner mounting components in CAD

## Portfolio Takeaway

This project gave me hands-on experience modifying and troubleshooting a real electromechanical system. What started as a power upgrade required me to solve problems involving fabrication, component fitment, drivetrain loading, gearing, electrical connections, braking, and performance testing.

One of the most useful parts of the project was being able to use a calculation to make a design change and then compare the prediction with a real test. The calculated top speed with the final gearing was **30.5 mph**, and the bike reached **29.2 mph** during testing.

The project helped me better understand how individual design decisions affect an entire mechanical system and why calculation, testing, and redesign are important parts of engineering.