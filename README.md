# Razor MX650 Performance Upgrade

## Project Overview

I upgraded a Razor MX650 electric dirt bike because I wanted it to have more power and a higher top speed than the stock setup. I started by replacing the motor, battery, and controller, but the project ended up requiring a lot more work than just swapping parts.

The larger components did not fit the stock frame without modifications, and once I started riding the bike I ran into problems with the gearing, chain, and brakes. I had to work through each problem and change the setup as I tested it.

## Stock vs. Upgraded

| | Stock MX650 | My Upgraded MX650 | Change |
|---|---:|---:|---:|
| Motor power | 650 W | 1800 W | **+177%** |
| Battery voltage | 36 V | 48 V | **+33%** |
| Battery capacity | 12 Ah | 20 Ah | **+67%** |
| Battery energy | 432 Wh | 960 Wh | **+122%** |
| Top speed | ~15 mph* | 29.2 mph measured | **+95%** |
| Rear tire | 14 in | 14 in | Same |

\*My bike went around 15 mph before the upgrades. Razor rates a stock MX650 at up to 17 mph.

The biggest change was the motor, going from the stock **650 W motor to 1800 W**, which is about **2.8 times the rated power**. The new battery also has more than double the rated energy capacity. My measured top speed went from around **15 mph before the build to 29.2 mph after the upgrades**, almost doubling the speed.

## Main Upgrades

| System | Upgrade |
|---|---|
| Motor | 48 V, 1800 W brushless motor |
| Battery | 48 V, 20 Ah battery |
| Controller | 48 V multivariable controller |
| Brakes | Upgraded brakes with a larger rotor |
| Drivetrain | 13T motor sprocket / 80T rear sprocket |
| Chain | Upgraded to a stronger chain after the smaller chain kept breaking |

## Motor Fitment and Fabrication

The new motor was much larger than the stock motor and did not fit directly into the MX650 frame.

I drilled clearance holes where I needed them to get the motor to fit. The motor also came with a mounting plate that took up too much room, so I cut the plate off and used the cylindrical motor body by itself. This gave me the extra clearance I needed inside the frame.

## Battery and Controller Installation

The 48 V 20 Ah battery was also much larger than the stock battery setup. I removed the upper stock battery holder to make room for it and flattened parts of the lower battery-holder walls that were in the way.

The controller did not come with the right connector for my battery, so I soldered the correct connector onto the controller wiring so everything could connect properly.

## Drivetrain and Gearing

The motor came with different sprocket options. I learned pretty quickly that the sprocket size made a big difference in how the bike actually rode.

### First Setup - 9T Sprocket

I first used a **9T motor sprocket with the 80T rear sprocket**. When my brother tested the bike, he said it had a lot of torque, but the top speed was only around **20 mph**. The stock bike went around **15 mph**, so after all of the upgrades I was only gaining about 5 mph.

I wanted to keep good acceleration but get the bike closer to 30 mph, so I decided to change the gearing instead of leaving the 9T sprocket on it.

### Choosing the 13T Sprocket

Instead of just trying different sprockets until one worked, I used the motor RPM, sprocket sizes, and rear tire diameter to figure out what would get me close to the speed I wanted.

My final setup was:

| Parameter | Value |
|---|---:|
| Motor speed | 4500 RPM |
| Motor sprocket | 13T |
| Rear sprocket | 80T |
| Rear tire diameter | 14 in |

I calculated the gear ratio using:

**Gear ratio = 80 / 13 = 6.15:1**

That means the motor turns about 6.15 times for every one turn of the rear wheel.

At 4500 motor RPM:

**Wheel RPM = 4500 / 6.15 ≈ 731 RPM**

Using the 14-inch rear tire, the calculated top speed came out to **30.5 mph**.

### Top Speed Calculation

![Top speed gear ratio calculation](Gear%20calculation%20for%20razor%20mx650%20by%20best-calculators.com.png)

The calculator also gave me **30.5 mph** using the 4500 RPM motor speed, 14-inch tire, and 6.15 gear ratio.

### Actual Speed Test

After putting the **13T sprocket** on the bike, I tested the top speed and got **29.2 mph**. That was very close to the 30.5 mph I calculated.

The bike did not hit the exact calculated speed, but there were a couple things working against it. The original wheel bearings were somewhat worn and the brakes were slightly grazing, which added resistance.

Going from the 9T to the 13T sprocket took the bike from around **20 mph to 29.2 mph**, so this ended up being one of the biggest improvements I made to the build.

### Wheel Torque Estimate

I also wanted to get an idea of how much torque the drivetrain was putting at the rear wheel. Using the 1800 W motor rating and 4500 RPM, I first estimated the motor torque.

**Angular speed = 4500 × (2π / 60) ≈ 471.2 rad/s**

**Motor torque = 1800 / 471.2 ≈ 3.82 N·m**

I then used my 6.15:1 gear ratio:

**Wheel torque = 3.82 × 6.15 ≈ 23.5 N·m**

So the calculated wheel torque is about **23.5 N·m** at that motor operating point. The actual amount at the wheel would be a little lower because some power is lost through the chain, bearings, and other parts of the drivetrain.

### Chain Problems

One of the problems I ran into after getting the bike running was the chain. The smaller chain I originally used kept breaking with the more powerful motor.

After it happened multiple times, I switched to a stronger chain instead of continuing to replace the same smaller one. After changing the chain and fixing the drivetrain setup, I tested the bike again to make sure the chain would stay on and the components stayed secure.

## Battery Range and Energy Use

My battery is **48 V and 20 Ah**, so I calculated its rated energy capacity as:

**48 V × 20 Ah = 960 Wh**

I got about **13.6 miles** during my range test.

Using the rated battery capacity:

**960 Wh / 13.6 miles ≈ 70.6 Wh/mile**

So the bike used an estimated **70.6 Wh/mile** during that test. This is not an exact measurement because I used the battery's rated 960 Wh capacity instead of measuring the exact amount of energy pulled from the battery, but it gave me a useful estimate of the bike's energy use.

## Brake Upgrade

The first riding test also showed that the stock braking setup was not good enough for the faster bike. My brother even pointed out the braking problem during the first test ride.

I upgraded the brakes and went with a larger rotor. I chose the larger rotor because moving the braking force farther away from the center of the wheel increases the braking torque.

**Braking torque = braking force × effective rotor radius**

Since I was making the bike faster, I wanted the braking system to improve along with the power and speed.

## Problems I Had to Solve

Some of the main problems I ran into were:

- Getting the larger motor to fit inside the stock frame
- Making enough room for the larger battery
- Modifying the stock mounting pieces
- Wiring the new battery and controller together
- Having too much torque and not enough speed with the 9T sprocket
- Choosing a better sprocket size for my target speed
- Repeatedly breaking the smaller chain
- Improving the brakes for the higher speed
- Finding the difference between my calculated and actual top speed

## What I Learned

The biggest thing I learned from this build was how changing one part can create problems somewhere else.

I originally thought the project would mainly be installing a bigger motor and battery. Once I actually started building and testing it, the extra power affected the motor fitment, battery placement, gearing, chain, and brakes.

The gearing was probably the best example. The 9T sprocket gave me a lot of torque but only around 20 mph. I used the measurements from my setup to choose the 13T sprocket, calculated about 30.5 mph, and then got 29.2 mph when I actually tested it.

I learned a lot more from fixing the problems that came up during testing than I would have from just installing parts that worked the first time.

## Skills Used

- Mechanical fabrication
- Electric drivetrain installation
- Component selection
- Gear-ratio calculations
- Motor and wheel torque calculations
- Battery and range calculations
- Testing and troubleshooting
- Brake-system improvements
- Soldering and electrical connections
- Packaging and clearance problem solving

## Project Videos

These videos show different stages of the build and testing.

### 1. Pre-Installation Electrical Test

[Watch the pre-installation electrical test](https://www.youtube.com/shorts/adXzm9Y-ZhQ)

After I wired the new electrical components, I tested everything while it was still outside of the bike. I wanted to make sure the motor, controller, and wiring worked before I went through the work of installing everything into the frame.

### 2. Components Installed in the Bike

[Watch the post-installation component test](https://www.youtube.com/shorts/GqMGUvGb6VI)

This shows the components after I installed them into the bike and where I was able to fit everything inside the frame. At this point I had not installed the chain and final drivetrain setup yet.

### 3. First Ride - 9T Sprocket

[Watch the first ride](https://www.youtube.com/shorts/6jxUeG4Upig)

This was the first riding test with the **9T motor sprocket**. My brother tested it and pointed out that it had a lot of torque but the brakes needed work. The bike was going around **20 mph** with this setup. This test is what made me start looking at changing the gearing and improving the brakes.

### 4. Drivetrain Test After Repairs

[Watch the post-repair riding test](https://www.youtube.com/shorts/k4TFucLBT2E)

This was after I fixed the chain and drivetrain problems. My brother rode and jumped the bike to put more load on it and make sure the chain stayed on and everything I installed stayed secure.

### 5. Finished Bike

[Watch the completed MX650 overview](https://www.youtube.com/shorts/-amuYUIw6IQ)

This is an overview of what the bike looked like when I finished the build.

## Future Improvements

There are still a few things I could improve or test later:

- Measure acceleration
- Measure braking distance
- Clean up and protect the wiring more
- Design cleaner mounting parts in SolidWorks

## Portfolio Takeaway

This project started as an upgrade to make my MX650 faster, but it turned into a lot of problem solving. I had to modify the frame setup, fit larger electrical components, solder wiring, change the gearing, fix chain problems, and upgrade the brakes.

My favorite part of the project was the gearing change because I was able to calculate what I thought the bike would do and then test it. I calculated **30.5 mph** with the 13T sprocket and the bike actually reached **29.2 mph**.

This project gave me hands-on experience building something, finding problems through testing, and then making changes to improve it.