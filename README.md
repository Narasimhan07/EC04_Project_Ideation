# EE04_Project_Ideation
## Problem statement   
The Digital Pen project aims at designing an electronic pen that stores text that is written manually on a surface automatically in a storage device. The text that is stored can be read and edited any time. The pen must be user-friendly, i.e, not very difficult to hold and use (not very large diameter), should be able to write on any size of paper.           
The basic functionality of the pen can be represented as follows,           
Writing on surface → motion sensors of some form → data processing → storage device
## Various Designs   
### Using CMOS and IMU sensors(sensors inside the pen)   
This technique is easier to implement compared to others because all the sensors can be fitted within the pen due to their small size. A custom PCB can also be designed to include 
the ICs for CMOS, IMU sensors and the microcontroller.    
### Using IMU sensor and Pressure sensor(sensors inside the pen)
Similar to the previous case, the pen design can be made compact and portable compared to a design having sensors on the outside.    
### Transceiver model using IR, Ultrasound or ToF based sensing (sensors outside the pen)    
These models are more comebursome than those with sensors inside. They also can limit the size of the paper used. For example, the ToF sensors have a range of 25 cm only. So the pen doesn't work very well for paper sizes larger than A4 sized papers.      
Ultrasound and IR sensors are prone to external interfrence from obstacles other than the nib of the pen. This can lead to false outputs or rogue data being stored.
