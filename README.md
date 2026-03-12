### Table of Contents

- Inspiration
- Brainstorming photos
- Component Research / Component list
- System Features
- Process and Progress
- Safety Precautions
- Final Product
- What I learned throughout the project
- Future Improvements  

# Inspiration

The inspiration for ScottyBot was to create a robot that integrates mobility, navigation, renewable energy, and interactive user communication into a single system. The goal was to create a project that was not only mechanical but also included electrical and software components. This project was especially interesting because it brought together different engineering ideas into a single build. Instead of focusing solely on movement or coding, ScottyBot became a combination of suspension design, navigation, solar integration, voice interaction, and AI-based responses.

# Brainstorming photos

1. <img width="368" height="447" alt="image" src="https://github.com/user-attachments/assets/70a9fc8f-bc88-4d04-b1ab-325a8585cf69" />
2. <img width="390" height="453" alt="image" src="https://github.com/user-attachments/assets/cee0868e-f57d-49f6-9226-e56f8597494e" />
3. <img width="393" height="470" alt="image" src="https://github.com/user-attachments/assets/004c80b6-c62a-4ae3-9d65-7b0c01659598" />
4. 
5. <img width="417" height="470" alt="image" src="https://github.com/user-attachments/assets/8512a8dd-b3ad-4365-8110-69574710feaa" />
6. <img width="481" height="447" alt="image" src="https://github.com/user-attachments/assets/1682796e-a0c7-416f-9f96-75cde78ab805" />
7. <img width="406" height="476" alt="image" src="https://github.com/user-attachments/assets/194bba6a-80e2-4960-a08d-820336322316" />
8. <img width="451" height="473" alt="image" src="https://github.com/user-attachments/assets/99dfaac8-6f17-4990-8ea7-7bd14e0f52be" />
9. <img width="472" height="476" alt="image" src="https://github.com/user-attachments/assets/52060101-ad71-46ef-8573-8ed29f3f0089" />
10.
11.  <img width="433" height="361" alt="image" src="https://github.com/user-attachments/assets/e73f32b4-df9c-46a6-a694-0066405aeccf" />
12. <img width="467" height="382" alt="image" src="https://github.com/user-attachments/assets/354f8374-9c01-404f-a4fd-2e0374efa76b" />
13. <img width="544" height="346" alt="image" src="https://github.com/user-attachments/assets/5b369edd-dea7-4c9a-9a01-748656aa9a3b" />
Design matrix:
<img width="2395" height="854" alt="image" src="https://github.com/user-attachments/assets/677e37bb-4d89-4fed-8e90-719f4bbc39a4" />


# Component Research/ Component list

Before building and integrating the system, research was conducted on the key components needed for ScottyBot. This included mechanical parts, electrical components, and software-related systems.

## Suspension
- Front wheel suspension components
- Mounting hardware
- Wheel support structure
The front suspension was added to improve wheel stability and enable the robot to better handle uneven surfaces. This also helped strengthen the mechanical design of the front section.

Components:
- Suspension hinge pins: 19.00
- Suspension shocks: 75.00
- Suspension shock towers: 10.00
- Suspesnion arms: 50.00

Total cost: 154.00

## Navigation System
- Distance display system
- Directional guidance logic
- Location input concept
The navigation system is currently relatively simple, but it can show the distance to a location and provide brief directions. This gives ScottyBot a basic navigation feature that can be expanded in the future.

Components:
- Raspberry Pi Pico self-startup kit, including OLED Screen: 20.00
- GPS Module: 12.50
- Magnometer Module: 10.00

Total Cost: 42.50

## Solar System
- Solar panel
- Power transfer to electronics
- Supplemental energy design
Solar power was added to the power system to support sustainability and demonstrate the use of renewable energy in the robot design.

Components:
- 300W Solar Panel with Solar controller: 35.00

Total cost: 35.00

## Battery and Electronics
- Battery
- Wiring connections
- Power distribution to electronics
The battery was wired into the electronics system so the robot could power its required components. Special attention was given to keeping the wiring organized and functional.

Components:
- 12V Battery: 46.00
- Motor Driver: 8.00
- Inline Fuses: 10.00
- Inline Fuse Blades: 5.00
- Electrical Wire: 10.00
- 5v DC to DC Buck Convertor: 6.00
- Breadboard wiring: 10.00
- Micro HDMI to HDMI: 15.00
- Velcro Sticky straps: 10.00
- 2 Arduino R3: 30.00

Total Cost: 150.00

## Voice Commands
- Voice input system
- Command recognition setup

Components:
- USB Microphone: 13.00
- Bluetooth speaker: 5.00

Total Cost: 18.00

## AI Response
- AI-generated response system
- User interaction support
An AI response feature was implemented to enable ScottyBot to respond during interactions. This adds an intelligent communication element to the project.

Components:
- Raspberry Pi: 75.00

Total cost: 75.00

# System Features

## Front Wheel Suspension

Suspension was added to the front wheels to improve balance and support smoother motion. This helps the robot maintain better stability and makes the structure more practical for movement.

## Navigation Display

The navigation feature can currently show distance to a place and provide small directional guidance. Although it is still basic, it establishes a foundation for future development into a deeper navigation system.

## Solar Integration

Solar integration was included as part of the robot’s design to support the electrical system and demonstrate an alternative energy source in the project.

## Battery to Electronics Wiring

The battery was connected to the electronics through the wiring system. This was an important step in making sure the robot’s different electrical features could operate together.

## Voice Command Capability

Voice command functionality allows ScottyBot to receive spoken input from the user. This improves the interaction between the robot and the user.

## AI Response Capability

ScottyBot can also produce AI-based responses, making the interaction more advanced and engaging.

# Process and Progress

## Sensor Setup

- <img width="736" height="977" alt="image" src="https://github.com/user-attachments/assets/d562ad54-ffa2-4d5d-a308-b0b875b09cf5" />
Set up the ultrasonic sensors on the Arduino before installing them on Scotty to make sure they work properly. Connected Vout and GND to the dedicated breadboard rails, and wired the trig and echo pins to alternating Arduino pins like D6, D7 for one sensor, and D8, D9 for another.
<img width="584" height="779" alt="image" src="https://github.com/user-attachments/assets/1f322232-d2a1-4a57-b62b-f6f0f8898925" />
Shows that the sensors work with the maximuim distance they can sense
<img width="563" height="318" alt="image" src="https://github.com/user-attachments/assets/7d5c5c25-cf3a-4aca-aa6f-cd3fae9aa9cc" />
A picture of the sensors lines up unfront of scotty

## Solar Setup

<img width="1045" height="780" alt="image" src="https://github.com/user-attachments/assets/390bfca1-fa4e-41a5-b397-39d79572788f" />
<img width="589" height="638" alt="image" src="https://github.com/user-attachments/assets/059c0f2d-e7f4-499c-a065-c586130c97bf" />
<img width="593" height="784" alt="image" src="https://github.com/user-attachments/assets/3ab94623-e1d7-4f87-9773-7c09e9b30218" />

## Suspension Setup

<img width="579" height="782" alt="image" src="https://github.com/user-attachments/assets/b7d9a974-068f-4271-9481-ec46619ae388" />
<img width="530" height="841" alt="image" src="https://github.com/user-attachments/assets/5fefdfc1-acef-40ae-a4ac-8ad534ba77bc" />
<img width="583" height="780" alt="image" src="https://github.com/user-attachments/assets/5f025960-b031-4f0c-b527-38a198b807c8" />
<img width="581" height="781" alt="image" src="https://github.com/user-attachments/assets/0e6a041b-2238-4bfe-9876-45cce9581e9d" />

## Ai setup

<img width="639" height="777" alt="image" src="https://github.com/user-attachments/assets/4423e050-b941-4506-b8e7-85e2a975ced7" />

## Wiring

<img width="584" height="783" alt="image" src="https://github.com/user-attachments/assets/0d1450d5-6c67-4746-b904-1fc47f1f7f0f" />
<img width="466" height="623" alt="image" src="https://github.com/user-attachments/assets/62eb5380-cda8-4bde-b97b-cbe00d48128a" />

# Safety Precautions

Safety precautions were considered during the battery and electronics wiring process. Care was taken to keep wiring organized, avoid unsafe connections, and reduce the chance of damaging electrical components.

This was an important part of the build because a working robot system depends not only on features being added, but also on making sure the electronics are connected in a safe and reliable way.

# Future Improvements

Although ScottyBot has made strong progress, several systems can still be expanded further.

- Improve the depth and accuracy of the navigation system
- Refine the mini direction system into a fuller guidance feature
- Improve power efficiency between the battery and solar system
- Expand voice command options
- Make AI responses more advanced and context-aware

ScottyBot currently has a strong base that combines mechanical design, power integration, and user interaction. Future work will focus on making each subsystem more polished and capable.

Process photos
=============
In progress
