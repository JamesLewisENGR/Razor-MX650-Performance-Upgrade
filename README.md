# Razor MX650 Performance Upgrade

## Project Overview

This project documents the mechanical and electrical redesign of a Razor MX650 electric dirt bike to significantly increase its performance, durability, and braking capability. The build required component selection, fabrication, drivetrain changes, electrical integration, and troubleshooting to adapt higher-power components to the original frame.

The project was completed as a hands-on engineering build focused on applying practical mechanical design and problem-solving skills.

## Engineering Objectives

- Increase available motor power and overall vehicle performance.
- Package a larger battery and upgraded electronics within the existing MX650 frame.
- Modify the frame and motor installation to resolve clearance and fitment constraints.
- Improve braking performance to better match the increased vehicle speed.
- Select drivetrain components that balance acceleration, top speed, and durability.
- Troubleshoot failures encountered during testing and revise the design accordingly.

## Major Upgrades

| System | Upgrade |
|---|---|
| Motor | 48 V, 1800 W brushless motor |
| Battery | 48 V, 20 Ah battery |
| Controller | 48 V multivariable controller |
| Braking | Upgraded brake system with larger rotor |
| Drivetrain | Modified sprocket/gearing configuration |
| Chain | Upgraded chain after the smaller original-style chain repeatedly failed under the increased load |

## Mechanical Fabrication and Integration

Several components could not be installed without modifying the original MX650 frame and hardware.

### Motor Fitment

The upgraded motor required physical modification for proper installation. Clearance holes were drilled where necessary so the motor could fit within the frame. The original mounting plate attached to the upgraded motor was also removed so that only the cylindrical motor body remained, allowing the motor to fit the available space more effectively.

### Battery Packaging

The larger 48 V 20 Ah battery required additional space compared with the stock battery system. Portions of the original battery mounting structure were removed or reshaped to create the necessary clearance while retaining the main frame structure.

### Electrical Integration

The upgraded controller and battery did not initially use the same connector configuration. The appropriate connector was soldered onto the controller wiring so that the new battery could be connected correctly.

This portion of the project required attention to polarity, connection quality, packaging, and strain relief.

## Drivetrain Design Decisions

The upgraded motor was supplied with different sprocket options. A smaller motor sprocket was selected to change the final drive ratio toward the desired performance characteristics.

Changing sprocket size changes the relationship between wheel torque and wheel speed. The drivetrain setup was selected with consideration for:

- Motor torque
- Desired top speed
- Acceleration
- Chain loading
- Available wheel sprocket size
- Reliability under the increased motor power

During testing, the smaller chain originally used in the setup repeatedly failed under the increased power. The drivetrain was therefore upgraded to a stronger chain, improving durability and demonstrating the need to account for increased transmitted load when power is increased.

## Brake Upgrade

Because the power upgrade increased the performance capability of the bike, braking performance also needed to be improved.

A larger brake rotor was installed. Increasing rotor diameter increases the effective moment arm at which the brake caliper applies force, allowing greater braking torque for the same caliper force.

The approximate relationship is:

**Braking torque = braking force × effective rotor radius**

This made the brake upgrade an important supporting modification rather than treating the motor upgrade as an isolated change.

## Engineering Challenges

Key challenges encountered during the project included:

- Packaging larger electrical components inside a frame designed for lower-power hardware.
- Resolving interference between the upgraded motor and the existing frame.
- Adapting incompatible electrical connectors.
- Selecting gearing appropriate for the upgraded power system.
- Managing the higher mechanical load transmitted through the chain.
- Improving braking capability to match the increased performance.

## Iterative Problem Solving

One of the most important parts of the project was responding to problems that appeared after assembly and testing.

For example, the initial chain configuration was not sufficiently durable for the upgraded power level. Rather than treating the failure as an isolated issue, the drivetrain was revised using a stronger chain better suited to the load. This reflects an iterative engineering process:

1. Build the system.
2. Test under operating conditions.
3. Identify the failure mode.
4. Determine the underlying cause.
5. Modify the design.
6. Retest the improved configuration.

## Skills Demonstrated

- Mechanical fabrication
- Electric drivetrain integration
- Component selection
- Gear-ratio reasoning
- Brake-system design considerations
- Electrical connector modification and soldering
- Packaging and clearance problem solving
- Troubleshooting and design iteration
- Hands-on prototyping

## Project Media

Photos and videos of the build, fabrication process, testing, and final bike will be added here.

### Video Demonstration

YouTube project video: **Coming soon**

### Build Photos

Project photos: **Coming soon**

## Future Improvements

Possible future engineering work could include:

- Documenting the exact motor and wheel sprocket tooth counts and calculating the final drive ratio.
- Measuring vehicle speed and acceleration before and after the upgrade.
- Estimating wheel torque from motor torque and gear ratio.
- Evaluating battery range and power consumption.
- Measuring braking distance after the rotor upgrade.
- Creating CAD models or brackets for cleaner component mounting.
- Improving wiring organization and component protection.

## Portfolio Takeaway

This project demonstrates the process of upgrading a real mechanical system where increased performance in one subsystem creates new requirements elsewhere. Increasing motor power affected component packaging, drivetrain loading, gearing, electrical integration, and braking requirements.

The project strengthened my understanding of how mechanical and electrical design decisions interact and showed the importance of testing, identifying failure modes, and iterating toward a more reliable design.
