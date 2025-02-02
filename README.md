This repository contains the code, presentaitons, and technical reports associated with the Cornerstone 1 Semester Deisgn Project. 

The assigned task for this project was to design and develop an autonomous robot that could compete and win in a 'Sumo-style' battle against another team's robot. The project was meant to utilize robotic elements 
and automations using various Arduino components, as well as sself-designed 3D printed, lasercut, and soldered components. The overarching goal of the design project was to follow the Engineering Design Cycle to comlete
this task. 

The rules of the 'Sumo Robot' competetion included: 
- Your team's robot must push the other robot out of the circle without leaving the circle itself
- The first robot to leave the circle (whether of its own accord or by being pushed out) would lose
- The robots were not allowed weapons or to flip the other robot
- The matches took place on a black mat with a 4ft diameter white circle that marked the edge of the arena, allowing the robots to utilize light sensors in order to stay within the circle
- The robot could not exceed a length of 16 inches, a width of 12 inches, or a weight of 3.5 lbs. 

For this project, our team needed to consider both the offenseive and defensive strategies requried to win these battles. Therefore, our design utilized creating a robot that was durable enough to withstand any attacking 
force from the opponent robot and uses offensive strategies to scan and attack its opponent. We developed a white shell that would protect the robots inner hardware from attack by the oponent and confuse the opponent's 
light sensors as a defensive measure. We also arranged the hardware compoenents of the robot in a way that made the center of mass of the robot as low as possible, in order to make it harder for the opponent to push it.

Additonally, as an offensive measure we developed custom wheels with a larger diameter than those originally provided which would increase the robot's speed without having to increasing the rpm of the motors, thus making 
it more effective at pushing the opponent out of the circle. Other offensive stratagies were developed in the code which was designed to use ultrasonic distance sensors to find the opponent and move toward them to push them 
out of the ring. 

In developing this project, we utilized Arduino IDE to write the code controlling the game. Additionally, we used Arduino components to hardwire the device, as well as 2D & 3D modeling software (Solidworks & Autocad) in order 
to design and fabricate the shell that housed our hardwiring. The final product, as shown in the technical report and presentaions, competed against other team's robots within across our grade. 
