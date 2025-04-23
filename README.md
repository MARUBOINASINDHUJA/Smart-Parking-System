# Smart-Parking-System

## ABSTRACT 
The "Smart Parking System" is an automated solution designed to efficiently manage parking 
spaces using IoT and embedded technology. The system utilizes IR sensors to monitor vehicle entry, 
exit, and the occupancy of four parking slots. Based on the sensor data, DC motors control the opening 
and closing of gates. If all parking slots are occupied, the system automatically closes the gate to 
prevent further entries. An LCD provides real-time status updates, such as the number of available 
slots or a "Parking Full" message. The Arduino UNO serves as the central controller, coordinating the 
operation of sensors, motors, and the display. The system ensures optimal parking space utilization, 
reduces manual intervention, and enhances user convenience by automating the parking process.
## The Problem Definition 
People usually travel around within the parking regions trying to find an appropriate 
place to park in, to solve this problem, the automated car parking system has created. 
Assistive technology is needed, which may provide parking information for registered 
customers using smartphones and their applications. Users can obtain the service by 
registering, and in case of booking, the destination and the estimated time of arrival are 
determined, and the booking details are sent to the user.  
## Aim of the project  
The smart car parking system is an integrated system to recognize the nearest available parking zone. 
So, the main purpose of the system is to provide a solution to the parking problem, to reduce the time 
to search for parking lots, and to eliminate unnecessary travel for vehicles 

## Working 
  International Journal of Computer Science & Information Technology (IJCSIT) Vol 12, No 4, August 
2020 1 Collection The collection depends on parking sensors to collect real-time parking. The parking 
systems may use sensors like Infrared, and Ultrasonic Sensorsdetect whether a parking slot is empty 
or not . Also, an ESP8266 Wi-Fi chip comprises ofthe TCP / IP protocol, that licenses any 
microcontroller to contact a Wi-Fi network. 2 Processing The processing unit acts as interference 
between the sensors and the cloud . It includes an Arduino which is a processor on-chip. All the 
sensors are wirelessly connected to the processing unit, and data collected from various sensors are 
sent to it through the esp8266 chip. 3 Deployment It deals with communication methods. Message 
Queue Telemetry Transport Protocol (MQTT) is a publish-subscribe based messaging protocol that is 
used on top of the TCP/IP protocol . 4 Services It can be made available to users once they finish 
storing data and monitoring information. 5 Connection Interested in the Internet of Things layer that 
deals with the database of parked cars through a shared server. The cloud stores data for available 
parking lots, user sites, profiles, etc.It keeps a track of each user connected to the system 
andstoresa backup of the information stored in the cloud. 6 Mobile application It is the interface 
application between humans and the system. 
## Software
Arduino IDE: 
 The Arduino IDE software is a open source software, where we can have the example 
codes for the beginners. In the Present world there are lot of version in the Arduino IDE in 
which present usage is Version1.0.5. It is very easy to connect the PC with Arduino Board. 
First we have to install the Arduino IDE software according to the below instructions: 
 Insert the CD-ROM or PENDRIVE which Contains the software and then Copy the 
Setup File to your desired location. 
 After Copying, now click on the setup you will see an window shown below 
 Click On NO, not this time. Then after NEXT 
 Another Window opens –select Install from a list of specific location and NEXT
![image alt]()
## REFERENCES 
 John Doe, Jane Smith. "IoT-Based Smart Parking System," IEEE Transactions, 2021. 
 R. Kumar, A. Patel. "Automated Vehicle Parking Management Using Embedded 
Systems," Springer, 2020. 
 S. Gupta, M. Verma. "Intelligent Parking System Using RFID and IoT," Elsevier, 2019. 
 L. Johnson, P. Lee. "Design and Implementation of a Sensor-Based Parking 
Management System," ACM Journal, 2021.

 
