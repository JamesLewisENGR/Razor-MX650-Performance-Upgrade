# Razor MX650 Performance Upgrade

## Project Overview

I upgraded a Razor MX650 electric dirt bike because I wanted more power and a higher top speed than I was getting from the stock bike. I started with the motor, battery, and controller, but once I got into the build I realized those parts were not just going to bolt right in.

I had to make room for the bigger components, change some of the wiring, and then deal with problems with the gearing, chain, and brakes once I started testing the bike.

## Stock vs. Upgraded

| | Stock MX650 | My MX650 | Change |
|---|---:|---:|---:|
| Motor power | 650 W | 1800 W | **+177%** |
| Battery voltage | 36 V | 48 V | **+33%** |
| Battery capacity | 12 Ah | 20 Ah | **+67%** |
| Battery energy | 432 Wh | 960 Wh | **+122%** |
| Top speed | ~15 mph* | 29.2 mph | **+95%** |
| Rear tire | 14 in | 14 in | Same |

\*My bike went around 15 mph before I started the build. Razor rates the stock MX650 at up to 17 mph.

The motor went from 650 W to 1800 W, and the new battery has more than twice the energy capacity of the stock one. The biggest difference I noticed was the speed. Mine went from around **15 mph before the build to 29.2 mph after it**.

## Main Upgrades

| System | What I changed |
|---|---|
| Motor | 48 V, 1800 W brushless motor |
| Battery | 48 V, 20 Ah battery |
| Controller | 48 V multivariable controller |
| Brakes | Larger rotor and upgraded brakes |
| Drivetrain | 13T motor sprocket / 80T rear sprocket |
| Chain | Stronger chain after the smaller one kept breaking |

## Motor Fitment and Fabrication

The new motor was a lot bigger than the stock one and would not fit in the frame as it came.

I drilled clearance holes where I needed them. The motor also came with a mounting plate that took up too much room, so I cut the plate off. That left me with the cylindrical motor body and gave me enough room to get it into the frame.

## Battery and Controller

The 48 V 20 Ah battery was also bigger than the stock batteries. I cut off the upper stock battery holder to make room and flattened parts of the lower battery-holder walls that were still in the way.

The controller had the wrong connector for my battery, so I soldered the right connector onto it.

## Drivetrain and Gearing

The motor came with different sprockets, and this ended up making a much bigger difference than I expected.

### First Setup - 9T Sprocket

I first ran a **9T motor sprocket with the 80T rear sprocket**. My brother tested the bike and said it had too much torque. It only went around **20 mph**, which was not what I wanted considering the stock bike had been going about **15 mph**.

I wanted to get it closer to 30 mph, so I decided to change the gearing.

### Choosing the 13T Sprocket

I did not want to keep buying sprockets and guessing, so I used the motor RPM, sprocket sizes, and tire diameter to see what a 13T sprocket should do.

| Measurement | Value |
|---|---:|
| Motor speed | 4500 RPM |
| Motor sprocket | 13T |
| Rear sprocket | 80T |
| Rear tire diameter | 14 in |

My gear ratio was:

**80 / 13 = 6.15:1**

At 4500 RPM that gives:

**Wheel RPM = 4500 / 6.15 ≈ 731 RPM**

Using the 14-inch rear tire, I got a calculated top speed of **30.5 mph**.

### Top Speed Calculation

![Top speed gear ratio calculation](Gear%20calculation%20for%20razor%20mx650%20by%20best-calculators.com.png)

I also put the same numbers into a gear-speed calculator and got **30.5 mph**.

### Actual Speed Test

Once I put the **13T sprocket** on, I tested the bike and got **29.2 mph**. That was pretty close to the 30.5 mph calculation.

The original wheel bearings were somewhat worn and the brakes were grazing a little, so there was some extra resistance that the calculation did not include.

The gearing change took the bike from around **20 mph with the 9T to 29.2 mph with the 13T**.

### Wheel Torque Calculation

I also wanted to learn how to calculate torque from motor power, RPM, and gearing. With the motor rated at 1800 W and 4500 RPM:

**Angular speed = 4500 × (2π / 60) ≈ 471.2 rad/s**

**Motor torque = 1800 / 471.2 ≈ 3.82 N·m**

Then I used the 6.15:1 gear ratio:

**Wheel torque = 3.82 × 6.15 ≈ 23.5 N·m**

This gave me a theoretical value of about **23.5 N·m at the rear wheel**. I did not have a way to directly measure the actual torque the bike was producing, so I could not compare the calculated number to a real measured torque value like I did with top speed.

For me, this calculation was mainly a learning exercise so I could understand how motor power, RPM, and gear ratio are used to estimate torque. It also helped me see how changing the gearing affects the torque available at the wheel.

### Chain Problems

The smaller chain I started with kept breaking once I was riding the bike with the new motor.

After replacing it more than once, I stopped using the same size and switched to a stronger chain. I tested it again afterward to make sure the chain stayed on and the rest of the setup stayed together under harder riding.

## Battery Range

The battery is **48 V and 20 Ah**, so:

**48 V × 20 Ah = 960 Wh**

On my range test I got about **13.6 miles**.

If I use the full rated 960 Wh for the calculation:

**960 Wh / 13.6 miles ≈ 70.6 Wh/mile**

So that works out to roughly **70.6 Wh/mile**. I did not have a wattmeter on the bike, so I did not directly measure exactly how many watt-hours I used. This is just based on the battery rating and the distance I got.

## Brake Upgrade

The brakes were another problem that showed up on the first test ride. My brother said the bike had a lot of torque but the brakes sucked, and I agreed they needed to be better if the bike was going to be faster.

I changed the brakes and used a larger rotor. The larger rotor gives the brake more leverage at the wheel because the braking force is acting farther away from the center.

**Braking torque = braking force × rotor radius**

## Problems I Ran Into

- The new motor would not fit in the stock frame
- The bigger battery needed more room
- The controller had the wrong battery connector
- The 9T sprocket had too much torque and not enough top speed
- The smaller chain kept breaking
- The brakes needed to be better for the higher speed
- The calculated speed and actual speed were not exactly the same

## What I Learned

I originally thought this would mostly be a motor and battery swap. Once I actually started building it, every change seemed to affect something else.

The gearing was probably the part I learned the most from. I started with the 9T sprocket and got around 20 mph. Instead of guessing on the next sprocket, I did the calculation for the 13T and got 30.5 mph. When I tested it, the bike actually did 29.2 mph.

The torque calculation was different because I could not measure the bike's actual wheel torque to check it. I still included it because learning how to calculate torque from power, RPM, and gear ratio was useful and helped me understand the drivetrain better.

I also learned that testing the bike was just as important as putting it together. The chain and brake problems did not really show up until I rode it.

## Skills Used

- Mechanical fabrication
- Electric drivetrain installation
- Soldering and wiring
- Gear-ratio calculations
- Motor and wheel torque calculations
- Battery and range calculations
- Component selection
- Testing and troubleshooting
- Brake upgrades
- Working around fitment and clearance problems

## Project Videos

### 1. Electrical Test Before Installation

[Watch the electrical test](https://www.youtube.com/shorts/adXzm9Y-ZhQ)

I wired everything outside of the bike first and tested it before installing it. I wanted to know the motor, controller, and wiring worked before I spent time fitting everything into the frame.

### 2. Components Installed

[Watch the component test](https://www.youtube.com/shorts/GqMGUvGb6VI)

This was after I got the electrical parts into the frame. The chain and final drivetrain were not installed yet.

### 3. First Ride - 9T Sprocket

[Watch the first ride](https://www.youtube.com/shorts/6jxUeG4Upig)

My brother tested the bike with the **9T sprocket**. It was doing around **20 mph**, had a lot of torque, and the brakes needed work. This test is why I changed the gearing and brakes.

### 4. Test After Fixing the Drivetrain

[Watch the drivetrain test](https://www.youtube.com/shorts/k4TFucLBT2E)

This was after I fixed the chain/drivetrain setup. My brother rode and jumped the bike so I could see if the chain stayed on and if everything I installed stayed secure.

### 5. Finished Bike

[Watch the finished bike](https://www.youtube.com/shorts/-amuYUIw6IQ)

This shows the bike after I finished the build.

## Things I Could Do Next

- Measure acceleration
- Measure braking distance
- Clean up and protect the wiring more
- Design better mounting parts in SolidWorks

## What I Took Away From the Project

This build ended up being a lot more than putting a bigger motor on a dirt bike. I had to cut and modify parts to make everything fit, solder the wiring, change the gearing, deal with the chain breaking, and improve the brakes.

The part I liked the most was getting the gearing calculation that close to the real test. I calculated **30.5 mph**, and the bike actually went **29.2 mph**.

The torque calculation was more of a learning exercise because I did not have a way to measure the actual wheel torque and compare it with the theoretical number. It still helped me understand how power, RPM, and gearing relate to torque.

The biggest thing I took away from it was that building something is only part of the process. Testing it, finding what does not work, and changing it is where I learned the most.