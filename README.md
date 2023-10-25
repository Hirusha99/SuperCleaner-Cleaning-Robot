# SuperCleaner-Cleaning-Robot

Our project offers a practical solution to everyday challenges, demonstrating the potential of robotics in enhancing human lives.

RoboTrack is a human-hand-following robot designed to assist people with various cleaning purposes like, work area cleaning, and mopping wet floors.

## Objectives

Efficiency - To efficiently clean various surfaces, including whiteboards, work areas, wet floors, and windows, without human intervention.

User Friendly - To design a robot that is intuitive to use, requiring minimal training for users of all backgrounds.

Safety - Prioritizing safety by implementing robust obstacle detection and avoidance mechanisms to prevent accidents.

## Components
Arduino Uno Board\
DC Motors\
IR Sensors\
Ultrasonic Sensors\
Servo Motor\
Motor Driver\
Wheels\
Battery (18650)\
Buzzer

## Nevigation

The code leverages an ultrasonic sensor for distance measurement and two IR sensors (Right and Left) for obstacle detection.
Ultrasonic sensor data is obtained using the NewPing library.
IR sensors assist in detecting obstacles and facilitating the robot's movements.

The code reads distance values from the ultrasonic sensor, providing real-time data about the robot's proximity to objects.

If the ultrasonic sensor detects that a human is within a specified range (1 to 15 cm), the robot proceeds to move forward.
When the robot detects an obstacle on one side, it initiates a turn in the opposite direction to avoid the obstacle. For example, if the Left IR sensor detects an obstacle, the robot turns to the right, and vice versa.

![WhatsApp Image 2023-10-22 at 6 26 28 PM](https://github.com/Hirusha99/SuperCleaner-Cleaning-Robot/assets/73214896/ee3596dd-8088-40bb-ab62-4ee192bcb89f)

![WhatsApp Image 2023-10-24 at 6 12 27 PM](https://github.com/Hirusha99/SuperCleaner-Cleaning-Robot/assets/73214896/a9d23464-0f5e-446e-89e8-a2eef12eac9b)

![WhatsApp Image 2023-10-22 at 6 26 26 PM](https://github.com/Hirusha99/SuperCleaner-Cleaning-Robot/assets/73214896/910b99b7-b7fd-40d6-8144-48bf81e5e399)

![WhatsApp Image 2023-10-22 at 6 26 25 PM](https://github.com/Hirusha99/SuperCleaner-Cleaning-Robot/assets/73214896/4d92e6c7-ef4e-4441-b298-4990153fd6a2)





