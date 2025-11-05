# Scotty Bot
<img width="693" height="928" alt="Image" src="https://github.com/user-attachments/assets/17872cd7-ae0f-4b0b-8c88-0e2ec8992839" />

### Table of Contents
[Inspiration](#inspiration)   
[Brainstorming photos](#brainstrsoming-photos)  
[Component Research](#component-research)  
[Cad parts screenshots](#cad-parts-screenshots)     
[Process photos](#process-photos)  
[Errors and Solutions](#errors-and-solutions)  

Inspiration
=============
The inspiration for improving Scotty Bot came from our own daily experiences as UCR students. Even as fourth-years, we realized there are still parts of campus we second-guess or have trouble finding, especially when buildings look similar or routes are confusing. After seeing new students struggle even more during tours and welcome events, it became clear how helpful a friendly, mobile guide could be. That idea — creating something that would genuinely make navigating campus easier — motivated us to redesign Scotty Bot into a more capable, dependable version of the mascot we all know. Our own challenges with directions, along with watching others hesitate or ask for help, shaped our vision for a robot that isn’t just a project, but a tool that can support students the moment they arrive at UCR.

Brainstorming photos
=============
<img width="746" height="761" alt="Image" src="https://github.com/user-attachments/assets/698801d9-9b81-4e5d-8911-76003ba76030" />

Component Research
=============
To develop the updated Scotty Bot, we conducted a focused evaluation of all major subsystems, comparing cost, performance, and integration requirements. All parts were tracked in a spreadsheet detailing unit price, total cost, vendor, quantity, and delivery lead time. I've included this spreadsheet above for reference. 
 
For sensing and navigation, we reviewed ultrasonic modules for close-range obstacle detection, a compact 2D LiDAR unit for mapping/localization, and lightweight vision cameras for optional interaction features. Control duties were split between a Raspberry Pi (high-level navigation and AI tasks) and an Arduino (motor, sensor, and safety-critical logic) to efficiently manage processing. 
    
In the power subsystem, we selected a low-cost 10–20 W rigid Renogy monocrystalline solar panel to reduce expenses while maintaining compatibility with a 12.8 V LiFePO₄ battery and CC/CV charge controller. LiFePO₄ cells were chosen for their stable discharge curve, long cycle life, and suitability for mobile systems. 
  
Mechanically, we evaluated rigid vs. suspended chassis designs and chose an RC-style independent suspension using small oil-filled coilover shocks. This improves traction during skid-steer motion, maintains wheel contact on uneven surfaces, and reduces vibration transmitted to the electronics. 
  
This component research ensured the design stayed cost-effective, durable, and technically scalable for future upgrades.
    
## AI / Navigation
### AI & Processing
 - Raspberry Pi (main brain)
 - Arduino (motor + safety control)
 - Speech recognition software (Vosk)
 - Text-to-speech system (Piper)

### Sensors
- Ultrasonic sensors
- LiDAR unit
- Camera (optional for interaction)

### Connectivity
- GPS for outdoor location
- SLAM for indoor mapping
- Motor driver + power interface

With these components in mind, we sought a lightweight AI setup that would run smoothly on a mobile robot. Using a Raspberry Pi alongside an Arduino gave us a simple split—navigation and AI on the Pi, and motor/safety control on the Arduino. We compared ultrasonic sensors and LiDAR to balance cost and performance, choosing a mix that keeps Scotty safe in tight spaces while still enabling accurate indoor and outdoor navigation.

## Suspension
### Shock / Damping Components
- RC-style coilover shocks (oil-filled)
- Upper/lower shock mounts
- Swing-arm or wheel-pod brackets
- Mounting hardware

### Frame Integration
- 3D-printed or aluminum suspension arms
- Reinforced chassis connection points
- Vibration isolators

### Performance Needs
- Maintain wheel contact
- Reduce chassis vibration
- Stability during skid-steer turning

When researching suspension options, we looked at RC vehicles like the Arrma Outcast to understand how compact oil-filled shocks handle uneven ground. This guided us toward components strong enough for Scotty’s weight. Switching from a rigid frame to independent suspension helps protect the electronics from vibration and improves traction over sidewalk joints and during turns.

## Soslar and Battery
### Solar Components
- Rigid 10–20 W Renogy monocrystalline panel
- Adjustable aluminum mounting brackets
- Solar wiring w/ protective insulation
- Weather-resistant connectors

### Battery / Charging
- 12.8 V LiFePO₄ battery (15 Ah)
- CC/CV charge controller
- Charging dock interface
- Safety fuse + cutoff switch

### Mounting
- Panel on rails / hood / front “tanning” concept
- Battery stored in the lower blue housing
- Cable routing through frame channels

For the power system, we switched from flexible panels to a cheaper, rigid Renogy option to cut costs while keeping good efficiency. We chose LiFePO₄ batteries for their safety and long lifespan. Mounting the panel, charge controller, and battery cleanly inside the frame made the system more reliable when powering the navigation, sensors, and AI together.

Cad parts screenshots
=============
In progress

Process photos
=============
In progress
