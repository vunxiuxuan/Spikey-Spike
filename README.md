# Table of Contents
- [Introduction](#introduction)
- [X-UniTech Team, Malaysia](#x-unitech-team-malaysia)
- [Performance video](#performance-video)

- [1.0 Mobility management](#10-mobility-management)
  - [1.1 Design of the self-driving car](#11-design-of-the-self-driving-car)
  - [1.2 Self-driving car steering](#12-self-driving-car-steering)
  - [1.3 Self-Driving Car Chassis](#13-self-driving-car-chassis)
  - [1.4 Building of the self-driving car](#14-building-of-the-self-driving-car)

- [2.0 Power and sense management](#20-power-and-sense-management)
  - [2.1 Power supply](#21-power-supply)
  - [2.2 Sensing elements](#22-sensing-elements)
  - [2.3 Build Of Materials (BOM)](#23-build-of-materials-bom)
  - [2.4 Electrical Diagram](#24-electrical-diagram)

- [3.0 Obstacle Management](#30-obstacle-management)
  - [3.1 Open Challenge](#31-open-challenge)
  - [3.2 Obstacle Challenge](#32-obstacle-challenge)

- [4.0 Engineering Factors](#40-engineering-factors)
- [5.0 Improvement and Enhancement](#50-improvement-and-enhancement)
- [Credits](#credits)

- [Appendix 1. Building Guide](#appendix-1-building-guide)
- [Appendix 2. Open Challenge Coding](#appendix-2-open-challenge-coding)
- [Appendix 3. Obstacle Challenge Coding](#appendix-3-obstacle-challenge-coding)


---

# Introduction
This engineering documentation covers the car’s mobility management, power and sensor systems, obstacle detection and avoidance, construction design, integration of third-party sensors, and the improvements made throughout our preparation for the World Robot Olympiad Open Championship Philippines (WRO) 2025 Future Engineers Category Competition.


# X-UniTech Team, Malaysia
X-UniTech from Malaysia is a team of three members who work together to build and program a self-driving robot car. We design, build, and manage all the electronic and mechanical parts to ensure our self-driving car runs smoothly. Here are our team members:

Vun Xiu Xuan, Alvin Kong Wei Ee, and Jennissa Aing Anak Jim.

<img width="365" height="257" alt="image" src="https://github.com/user-attachments/assets/94ed1629-ecbe-4753-b304-82196dfb93b9" />
<img width="364" height="264" alt="image" src="https://github.com/user-attachments/assets/61939f01-f833-4bdd-a935-b3ae4eac5847" />


# Performance video
This video provides an overview of our self-driving car’s design, demonstrates its performance in both the Open Challenge and the Obstacle Challenge, and explains how it operates in each scenario. Scan the QR code below to watch the video for both challenges.

<img width="170" height="170" alt="image" src="https://github.com/user-attachments/assets/9bbcebce-97f9-4f66-90e7-144bb1c3e386" />


# 1.0 Mobility management
This section explains how our self-driving car is designed, how the motors are used to control its movement, and how they are connected to the vehicle. It also describes the chassis and where different parts are placed. Lastly, it introduces basic engineering ideas like speed, torque, and power that affect how the car works.

## 1.1 Design of the self-driving car
The autonomous self-driving car is constructed using the LEGO® Education SPIKE™ Prime Set (45678). The building instruction of the robot can be obtained through Appendix 1.

<img width="421" height="320" alt="image" src="https://github.com/user-attachments/assets/581cd337-0342-4d8c-be64-4b94f0005a98" />

The figure below displays the images of the self-driving car that we have designed and constructed.

Top view

<img width="278" height="352" alt="image" src="https://github.com/user-attachments/assets/d797660d-8ddc-48a5-9bd6-ace861b8d62d" />

Bottom view

<img width="274" height="357" alt="image" src="https://github.com/user-attachments/assets/88242760-9098-416e-b77d-00b97f1aec5f" />

Front view

<img width="256" height="415" alt="image" src="https://github.com/user-attachments/assets/942659d2-5951-46be-be04-9ba0c7c0bdef" />

Back view

<img width="270" height="407" alt="image" src="https://github.com/user-attachments/assets/1d7c971a-5fcc-4efe-8b53-8c9fc95322d7" />

Left side view

<img width="292" height="363" alt="image" src="https://github.com/user-attachments/assets/3c572084-4fd4-4db5-bccc-672b7c97088a" />

Right side view

<img width="275" height="374" alt="image" src="https://github.com/user-attachments/assets/e9d6c57d-101b-4a01-bf2f-aad40415e3f6" />


## 1.2 Self-driving car steering
Our design applies Ackermann steering geometry, where the front wheels turn at slightly different angles. This allows the inner and outer wheels to follow separate paths during a turn, minimizing slip and friction. As a result, the vehicle remains stable, the tires are more durable, and it can handle sharp turns without skidding or losing balance.

<img width="482" height="364" alt="image" src="https://github.com/user-attachments/assets/5e7cc2a3-302b-4a35-a966-f7ef55225c2f" />


## 1.3 Self-Driving Car Chassis
The chassis design of the self-driving car plays a crucial role in providing structural integrity and maintaining stability during fast maneuvers, including sharp turns and sudden accelerations. The robot implements the differential gear to help its run smoothly. The differential gear transfers power between the two axles, enabling them to rotate at different speeds. This mechanism allows the self-driving car to execute smooth turns, especially when navigating around inner wall corners during Open Challenge.

<img width="583" height="326" alt="image" src="https://github.com/user-attachments/assets/20a0eec0-488a-46f6-98cb-42f9f94fc4b1" />


## 1.4 Building of the self-driving car
The building instruction for the self-driving car and the video of showcasing the 3D printing process of its parts can be accessed via the QR Code below. 

Building Instruction of Self-Driving Car (PDF format)

<img width="169" height="166" alt="image" src="https://github.com/user-attachments/assets/84b507fb-da3f-4259-957c-2d6b2044f6f6" />


# 2.0 Power and sense management
This section highlights the critical pieces that sustain the reliable operation and intelligent functionality of the LEGO® SPIKE Prime Self-Driving Car.

## 2.1 Power supply
The power supply is provided by the LEGO® SPIKE Prime rechargeable hub, delivering stable energy to motors, sensors, and the control unit while minimizing fluctuations that could disrupt performance. 

<img width="312" height="393" alt="image" src="https://github.com/user-attachments/assets/e1bc99b1-76cc-4c4a-b0ea-3fc9ed291063" />

## 2.2 Sensing elements
This section introduces the sensors that are used on the Self-Driving Car. Sensors form the core perception system of the LEGO® SPIKE Prime vehicle, enabling it to detect, interpret, and respond to its environment.

<img width="693" height="390" alt="image" src="https://github.com/user-attachments/assets/6f80bb5e-53f8-497b-8eff-a15983760f70" />

i) Distance Sensor of LEGO® Education SPIKE™

The Spike Distance Sensor is used on our robot to detect the distance between the robot and the wall. In the Open Challenge, we used the distance sensor to keep the robot aligned with the wall and to perform turns when the wall was no longer detected nearby. In the Obstacle Challenge, the distance sensor was used to detect the wall and the boundaries of the parking lot before doing the parking.

<img width="683" height="249" alt="image" src="https://github.com/user-attachments/assets/66222240-e6c7-4ea7-80dc-54b320da52ca" />

ii) Color Sensor of LEGO® Education SPIKE™

The Spike Color Sensor is used to detect the blue or orange lines on the map. In the Obstacle Challenge, we used the color sensor to detect these lines at corners, allowing the robot to determine for turning.

<img width="664" height="292" alt="image" src="https://github.com/user-attachments/assets/ddaff904-1961-4db1-8290-489f90c0bb53" />

iii) Build-in Gyro Sensor in LEGO® SPIKE Prime hub

The built-in gyro is used to keep the robot moving in a straight line and to perform turns accurately. The Spike built-in gyro calculates the robot’s angle precisely, ensuring that its movement remains straight. 

<img width="527" height="342" alt="image" src="https://github.com/user-attachments/assets/87f477eb-b0e2-4f70-8d37-8d4ae58630ba" />

iv) ESP-32 Cam

The ESP-32 Cam was used by our team to detect obstacles on the map during the Obstacle Challenge. The camera helps the robot identify the color of the pillars and decide whether to avoid them by turning left or right.

<img width="640" height="233" alt="image" src="https://github.com/user-attachments/assets/f85478f3-3d67-4284-bb11-56f57ed0de9c" />


## 2.3 Build Of Materials (BOM)
List below shows the parts of LEGO® Education SPIKE™ Prime Set (45678) that is used for the assembly of the Self-Driving Car.

<img width="561" height="798" alt="image" src="https://github.com/user-attachments/assets/eb5b080c-686d-4f11-9f41-465d1ad2880b" />

<img width="610" height="851" alt="image" src="https://github.com/user-attachments/assets/72f58e9b-d0a7-4e07-b21d-e1f066016496" />

<img width="591" height="818" alt="image" src="https://github.com/user-attachments/assets/afa2f383-17a7-497e-8023-7ff3bddb79f0" />

<img width="608" height="803" alt="image" src="https://github.com/user-attachments/assets/87c8b1d9-33ad-4754-b72e-9c3c4fea285f" />

<img width="564" height="807" alt="image" src="https://github.com/user-attachments/assets/bcd4c8b5-b6b9-4431-90ed-6564f5c3e074" />

<img width="570" height="316" alt="image" src="https://github.com/user-attachments/assets/616c948e-3bfb-4724-ac60-9e8311def7a8" />

<img width="586" height="801" alt="image" src="https://github.com/user-attachments/assets/0c8dfe89-c7da-485e-b99b-cf457c9f11f3" />


## 2.4 Electrical Diagram
The wiring diagram presents the interconnections linking the power supply, central hub, sensors, and actuators. It gives a guide for the system assembly, fault detection and ongoing maintenance.

(i) Open challenge wiring diagram 

<img width="684" height="440" alt="image" src="https://github.com/user-attachments/assets/e2617edb-3429-4bc4-a4e8-094142bebacb" />

(ii) Obstacle challenge wiring diagram

<img width="579" height="422" alt="image" src="https://github.com/user-attachments/assets/ccd62e14-33ca-4193-9fb5-3c009c247766" />


# 3.0 Obstacle Management
In our project, we utilize the LEGO Education Spike programming language to operate the robot. The programming structure is divided into two main sections which is the Open Challenge and the Obstacle Challenge. This section includes a flowchart and an overview of the code used for both challenges. 

## 3.1 Open Challenge
The right distance sensor is used to determine whether the vehicle goes clockwise or counterclockwise during the Open Challenge round while left and right distance sensors are used to maintain the distance of the self-driving car between the inner and outer walls. The vehicle needs to complete 12 rounds to finish the challenge. Below shows the flow chart for the Open Challenge.

<img width="809" height="439" alt="image" src="https://github.com/user-attachments/assets/37b4fc20-8d17-4f49-a327-83e2a945581a" />

Appendix 2 contains the complete programming code for the Obstacle Challenge. 
We will have a look at the details for the coding of Open Challenge.

<img width="694" height="292" alt="image" src="https://github.com/user-attachments/assets/bac88d30-ea31-4cb0-87a4-9916aa2e8a60" />

This part of the program is used to calculate the values from the gyro sensor in order to keep the robot moving in a straight line. By continuously reading the orientation data from the gyro, the robot can detect even small deviations from its intended path. These values are then processed and used to make corrective adjustments to the motors, ensuring the vehicle maintains a stable and accurate trajectory. This function is very important, as it prevents the robot from drifting sideways and helps it stay aligned while performing autonomous tasks.

<img width="457" height="289" alt="image" src="https://github.com/user-attachments/assets/25e080b6-09de-4e64-bfcc-f4bb0368bf0c" />

This part of the program is responsible for reading the values from both the gyro sensor and the ultrasonic sensor. The gyro provides orientation data that helps the robot maintain its direction and stability, while the ultrasonic sensor measures distances to nearby objects. By combining these two inputs, the robot can not only move in a straight line but also avoid obstacles effectively. This integration of sensor data is important for improving navigation accuracy and ensuring the robot can adapt to changes in the environment while completing its tasks.

<img width="339" height="408" alt="image" src="https://github.com/user-attachments/assets/e58c13d1-0951-44ff-89d5-5706b0552d14" />

This part of the program is used to reset the steering system at the beginning of the run. It ensures that the front wheels of the robot are aligned at the centre position when the program starts. By doing this, the robot begins in a neutral steering state, which provides a stable baseline for all subsequent movements. This step is important because any misalignment at the start could cause the robot to drift or turn unintentionally, affecting the accuracy of navigation and task performance.

<img width="609" height="824" alt="image" src="https://github.com/user-attachments/assets/d418b5e2-d0fd-4e6b-b070-fbb561f74dbf" />

This part of the program is responsible for calculating the steering angle of the robot. By determining the exact angle, the system can adjust the front wheels more precisely, allowing the robot to turn with greater accuracy and stability. This calculation helps reduce unnecessary friction and prevents sudden or jerky movements during a turn. As a result, the steering becomes smoother, and the robot can navigate corners or curves more efficiently while maintaining balance and control.

<img width="694" height="263" alt="image" src="https://github.com/user-attachments/assets/9402cf69-19f5-4c04-8eae-b5d2fb36819c" />

This part of the program combines the values received from multiple sensors, including the gyro, ultrasonic sensor, and colour or vision sensors. By processing these inputs together, the robot can make smarter decisions while navigating. The combined data is used to control the steering system when making turns and to ensure that the robot avoids walls or other obstacles in its path. This sensor fusion approach allows the robot to react more accurately to its environment, providing smoother turns, better obstacle avoidance, and more reliable performance during the challenge.

<img width="554" height="384" alt="image" src="https://github.com/user-attachments/assets/2f09dca2-a900-429f-9af3-d09fc622ce60" />

This block is used to control the movement of the robot by rotating the rear wheels according to a specified number of degrees. By setting the wheel rotation in degrees, the program can precisely determine how far the robot should travel. This method provides better accuracy compared to timed movements, as it is directly based on the wheel’s rotation. It helps ensure consistent and predictable motion, which is important for completing tasks and following the planned path.

<img width="628" height="432" alt="image" src="https://github.com/user-attachments/assets/21bee5bb-63e4-4a48-b303-6248d1f7c8a1" />

This block is used to control the movement of the robot based on the number of degrees that we input. By specifying the rotation in degrees, the program can accurately determine the distance the robot should travel. This approach makes the movement more consistent and reliable, as it directly relates to the wheel’s rotation rather than relying on time-based control. It allows the robot to perform tasks with better precision and follow the planned route more effectively.

<img width="279" height="359" alt="image" src="https://github.com/user-attachments/assets/9fb2b8f5-dce9-4d2e-a490-7b796e070e81" />

This block is used to set the origin values for all the variables in the program. By initializing these variables at the start, the robot begins its operation with a clean and consistent baseline. This step is important because it prevents errors that might occur if the variables still hold old or undefined values from previous runs. Proper initialization ensures that all sensors, counters, and control parameters start from the correct reference point, allowing the robot to function accurately and reliably throughout the task.

<img width="697" height="492" alt="image" src="https://github.com/user-attachments/assets/4b71d32f-03da-44c4-af12-a02f1182a3ef" />

This block represents the start of the main program, where the robot determines whether it should move in a clockwise or counterclockwise direction. At this stage, the robot reads input from its sensors, such as the camera or color detector, to analyse its surroundings and decide the correct orientation. This decision is crucial because it sets the initial path for the robot, influencing how it will navigate the rest of the challenge. By establishing the direction at the very beginning, the program ensures that the robot follows a consistent and reliable strategy throughout its tasks.

<img width="479" height="787" alt="image" src="https://github.com/user-attachments/assets/ae8868e8-accd-49a1-a622-ed4e7190c5ba" />

This block represents the main loop of the program, where the robot is programmed to move a certain number of degrees that have been predetermined. The robot continues this movement until it detects a line on the map using its color sensor. Each time this process is completed, it is counted as one loop. The robot is designed to repeat this cycle a total of 11 times to fulfill the challenge requirements. After completing the loops, the robot then moves an additional 1000 degrees to return to the starting area, ensuring the task is finished accurately and consistently.

## 3.2 Obstacle Challenge
The ESP-32 cam is added in to assist the robot identifying the pillars during the round. Below shows the flow chart for the coding of Obstacle Challenge.

<img width="755" height="389" alt="image" src="https://github.com/user-attachments/assets/48f8bf8d-bbf8-410b-85d2-ce0ba6135270" />

Appendix 3 contains the complete programming code for the Obstacle Challenge. 

We will have a look at the details for the coding of Open Challenge.

<img width="605" height="242" alt="image" src="https://github.com/user-attachments/assets/ff6fa146-333f-4c47-9442-26c85ae45957" />

<img width="324" height="359" alt="image" src="https://github.com/user-attachments/assets/3dc76c79-8a8a-4922-8a3e-54c61dbbb9b6" />

Above coding is used for the set up of the build-in gyro, colour sensor, ultrasonic sensor and camera on the robot. This part is used to save the sensor data into a variable.

<img width="398" height="528" alt="image" src="https://github.com/user-attachments/assets/392508e2-2cda-4146-85a2-efbb15b0b4d7" />

 This simplified block is used for the steering. This block help steering had a more sensitive and accurate angle to turn. 

 <img width="293" height="302" alt="image" src="https://github.com/user-attachments/assets/add15679-70a8-4610-b02f-fbb7ca532988" />

<img width="422" height="307" alt="image" src="https://github.com/user-attachments/assets/7c3a0678-6095-4a3b-966c-6f75f021a9bf" />

This block is known as ‘Drive’. This block is used to calculate all the sensor data and combine all of them to control the steering turning.

<img width="372" height="235" alt="image" src="https://github.com/user-attachments/assets/40c24e5c-094e-40d3-8dca-8eb8b25d3da3" />

<img width="336" height="236" alt="image" src="https://github.com/user-attachments/assets/8bf13558-46f1-4efe-bfa4-a74c61db08cb" />

This block is known as ‘Drive Degrees’ which is used to move the robot by calculating the degrees of the rear wheel turning until the degrees that we need and the robot will stop.

<img width="268" height="637" alt="image" src="https://github.com/user-attachments/assets/87ede3eb-4081-4333-bff3-183cf3513ca7" />

<img width="406" height="543" alt="image" src="https://github.com/user-attachments/assets/a9110850-03ae-4e35-8e13-e87a288473e8" />

This block is known as ‘Steering Drive’ which used for turning the robot with the calculation of the rear wheel degrees.

<img width="246" height="329" alt="image" src="https://github.com/user-attachments/assets/ea1c5192-3a9f-41cb-8676-ede269397cbc" />

This simplified block is known as ‘Drive 3 Round’. This block is the programme that is used for turning the map for three rounds. The robot will move 1000 degrees and move until it detects a colour line on the map and will add on 90 degrees to turn. This will be known as a loop and the robot will repeat the loop for 12 times.

Below is the main program to set an original value for all the variables.

<img width="404" height="332" alt="image" src="https://github.com/user-attachments/assets/49f6be00-c3d3-48d9-b067-b94891e991bf" />

This section of the robot’s function is specifically designed to handle the process of exiting the parking zone and making directional decisions. When the robot comes out of the parking area, it needs to determine whether it should move clockwise or counterclockwise around the arena. This decision is based on the input received from its sensors, which analyse the surrounding environment and detect possible obstacles or reference markers. By doing so, the robot ensures that it follows the correct path while avoiding collisions and maintaining smooth navigation. This step is crucial because it sets the initial direction of movement, which will affect how the robot approaches the rest of the tasks in the challenge.

<img width="404" height="662" alt="image" src="https://github.com/user-attachments/assets/89f6bd22-ff70-4870-bbf1-6cfb9ec1dc24" />

This part of the program is responsible for enabling the robot to detect a colored line on the map, which acts as a signal for the robot to make a turn. At the same time, the system also keeps track of how many loops the robot has completed. By combining line detection with loop counting, the robot can follow the course more accurately and avoid getting lost. This feature is especially important because it allows the robot to understand its position on the track and make sure it performs the required number of turns and laps according to the challenge.

<img width="370" height="689" alt="image" src="https://github.com/user-attachments/assets/644d3f23-af06-497a-9caf-2f6c449af361" />

 This part of the program is designed for the robot to search for the magenta-colored wall, which acts as a key marker in the challenge. Once the wall is detected, the robot uses this information to decide its parking strategy, specifically whether it should park in a clockwise or counterclockwise direction. By recognizing the magenta wall as a reference point, the robot can make a clear decision on how to approach the parking zone, ensuring accuracy and consistency in its movement. This process is important because it allows the robot to adapt its path based on visual cues, rather than following only pre-set movements.


# 4.0 Engineering Factors
This section highlights our custom-built and third-party open-source components, accompanied by detailed descriptions of each part integrated into the car.
Our robot used a third-party component which is a 3D printed camera holder. A 3D-printed camera holder is used to securely mount the sensor, ensuring it remains stable even during motion or sharp turns. This stability allows the ESP32-Cam to consistently capture crucial data for recognizing and interpreting traffic signs, thereby enhancing the robot’s responsiveness to its surroundings and improving performance in both the Open Challenge and Obstacle Challenge.

<img width="493" height="335" alt="image" src="https://github.com/user-attachments/assets/4f64ec48-b90b-40a2-9c37-0499ad8dbedf" />


# 5.0 Improvement and Enhancement
This section describes the challenges encountered during the development of our self-driving car and the approaches we applied to overcome them. Through careful analysis of each issue, we introduced modifications that enhanced the car’s overall performance.
One of the issues we faced during the challenge is the wheels tended to hit walls during traffic sign avoidance, so we added crash barriers on both sides of the robot. 

<img width="474" height="440" alt="image" src="https://github.com/user-attachments/assets/3f5ae6b3-2652-440c-bac8-0943823a8311" />

These barriers act as buffers, redirecting the robot away from obstacles before the tires make contact. This reduces friction and prevents the robot from getting stuck, allowing it to move smoothly without obstruction.
Another issue we worked on was in the programming. In the Open Challenge, we initially used the color sensor to scan the line (orange for clockwise and blue for anticlockwise) so the robot could decide when to turn left or right. However, the color sensor sometimes failed to detect the line, which caused the robot to miss turns. 

<img width="546" height="233" alt="image" src="https://github.com/user-attachments/assets/2392b565-dbde-45e4-b3b8-c967902fe6c2" />

To overcome this, we replaced the color sensor with the ultrasonic sensor. With this improvement, the ultrasonic sensor measures the distance from the wall, and if the value is greater than 2000, the robot recognizes that it has reached the edge of the wall and makes the turn. This adjustment increased the robot’s accuracy and reliability, ensuring smoother navigation throughout the challenge.

<img width="552" height="230" alt="image" src="https://github.com/user-attachments/assets/c605cd91-389b-4380-9957-00affbb12061" />


# Credits
We acknowledge the use of LEGO® Education SPIKE™ Prime in this project.  LEGO®, the LEGO logo, and SPIKE™ are trademarks of the LEGO Group.  This project is an independent creation and is not sponsored, authorized, or endorsed by the LEGO Group.

# Appendix 1. Building Guide
<img width="684" height="484" alt="image" src="https://github.com/user-attachments/assets/8eed9e42-acb8-400e-88c7-6d6af1c0f976" />

<img width="696" height="489" alt="image" src="https://github.com/user-attachments/assets/33a44102-5c68-42a6-9b81-10c1a9325426" />

<img width="728" height="515" alt="image" src="https://github.com/user-attachments/assets/ad5fc535-18e4-448e-88ca-fbf56857df65" />

<img width="728" height="514" alt="image" src="https://github.com/user-attachments/assets/91fd6fc2-eca5-4349-a1a1-027f944a74a4" />

<img width="697" height="492" alt="image" src="https://github.com/user-attachments/assets/4f03e17c-65d6-47ae-accd-a0a37e060be2" />

<img width="670" height="473" alt="image" src="https://github.com/user-attachments/assets/9dd5e5f4-3f82-4a25-a18c-d5f9ef4ca7e3" />

<img width="715" height="506" alt="image" src="https://github.com/user-attachments/assets/421c848a-5804-4905-b5af-6ea84d6fc5cb" />

<img width="705" height="497" alt="image" src="https://github.com/user-attachments/assets/cea12209-6630-45f1-bf24-3f3e6b525316" />

<img width="731" height="516" alt="image" src="https://github.com/user-attachments/assets/3dfa35b0-a3b6-4f34-b787-ea75a981d08b" />

<img width="765" height="541" alt="image" src="https://github.com/user-attachments/assets/1253d7ff-ba16-4f98-9f83-f929fe99bd5e" />

<img width="736" height="520" alt="image" src="https://github.com/user-attachments/assets/8d17bb45-78a2-4532-b7b8-590d87909877" />

<img width="726" height="513" alt="image" src="https://github.com/user-attachments/assets/b96d340d-fd32-4e07-a6ea-d3d84a67e030" />

<img width="735" height="519" alt="image" src="https://github.com/user-attachments/assets/8f3695e1-25cc-4164-a870-74e1addf4bca" />

<img width="749" height="529" alt="image" src="https://github.com/user-attachments/assets/6b1dae21-cd34-4f29-a888-5b8304d0bf98" />

<img width="739" height="522" alt="image" src="https://github.com/user-attachments/assets/053d6599-f49e-4e3f-a7b3-3ec5c63b32f7" />

<img width="749" height="529" alt="image" src="https://github.com/user-attachments/assets/fde2a1ce-fa65-4763-ae7a-e93a53867ffa" />

<img width="746" height="527" alt="image" src="https://github.com/user-attachments/assets/fe0943db-5cc4-4d5f-beae-2e31fe47d1ff" />

<img width="750" height="531" alt="image" src="https://github.com/user-attachments/assets/def1fba3-0051-476c-b311-f07170ffedc8" />

<img width="737" height="521" alt="image" src="https://github.com/user-attachments/assets/efd1bcae-e955-4a96-bcba-7272bcae16fd" />

<img width="744" height="526" alt="image" src="https://github.com/user-attachments/assets/829898c4-0d69-4fe4-98b3-fac6a79f13a8" />

<img width="716" height="505" alt="image" src="https://github.com/user-attachments/assets/85a0994e-945e-4e09-8eac-03110ef64948" />

<img width="739" height="522" alt="image" src="https://github.com/user-attachments/assets/1b261b0a-ff4b-4a12-9f24-77cc69536336" />

<img width="755" height="534" alt="image" src="https://github.com/user-attachments/assets/1ba7e073-8ee9-4f12-a7d3-ff451319343e" />

<img width="749" height="529" alt="image" src="https://github.com/user-attachments/assets/2a39918b-ee81-4d1d-bd4b-eedd9448e62a" />

<img width="747" height="527" alt="image" src="https://github.com/user-attachments/assets/a0ccec9e-ed20-4a4d-96bc-84f4add346fb" />

<img width="751" height="531" alt="image" src="https://github.com/user-attachments/assets/c5775b52-48a5-416d-b64f-76d2fa6aa31d" />

<img width="728" height="515" alt="image" src="https://github.com/user-attachments/assets/d3da9180-77c2-4e06-82b5-2250bee90c9f" />

<img width="754" height="533" alt="image" src="https://github.com/user-attachments/assets/c9e130fc-7c72-40ab-bbd6-93627bec207b" />

<img width="756" height="534" alt="image" src="https://github.com/user-attachments/assets/e7abe334-3d25-4044-9757-400441724016" />

<img width="745" height="526" alt="image" src="https://github.com/user-attachments/assets/715f417b-b9fb-44cc-97b9-d793ec20d4b4" />

<img width="735" height="520" alt="image" src="https://github.com/user-attachments/assets/b6302d4f-7cd8-48da-8a12-a30eb26981af" />

<img width="740" height="523" alt="image" src="https://github.com/user-attachments/assets/f9d5edce-21ac-48b2-b8de-775bd95f6a0d" />

<img width="746" height="528" alt="image" src="https://github.com/user-attachments/assets/1adf76f4-9a88-4346-a073-409895e70af8" />

<img width="760" height="537" alt="image" src="https://github.com/user-attachments/assets/327bca9a-8771-410a-89d4-db91ea21ea63" />

<img width="747" height="527" alt="image" src="https://github.com/user-attachments/assets/e1d2cc84-dfdd-4825-adad-0c57f429be01" />

<img width="756" height="534" alt="image" src="https://github.com/user-attachments/assets/a195e506-e653-491a-b5ef-c6036b063504" />

<img width="755" height="534" alt="image" src="https://github.com/user-attachments/assets/29f26620-4c2c-443f-b1e9-f7114bfd8947" />

<img width="746" height="526" alt="image" src="https://github.com/user-attachments/assets/d509193b-f1d6-43dc-9f30-bd6d66e9c87a" />

<img width="748" height="527" alt="image" src="https://github.com/user-attachments/assets/48ed8dfb-c97e-4305-a9e3-41a978453139" />

<img width="760" height="537" alt="image" src="https://github.com/user-attachments/assets/18d7eaf0-c6c2-4d34-8695-09df9a1e1326" />

photo 41 blum



# Appendix 2. Open Challenge Coding

# Appendix 3. Obstacle Challenge Coding

