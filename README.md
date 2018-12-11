# TEMP102 (Temperature sensor)

A sensor which records the temperature readings of the surroundings.

## PURPOSE
<BR>
  
The sensor will give temperature readings of the objects like battery and circuit board so that we can detect whether it is damaged or  it can still work . Like it can be used to test the temperature for multiple objects in a particular device such as smart phone, laptop. Also for example it can be used to record the temperature readings of the device called  drone .


## COMPONENTS REQUIRED 
<BR>
  
  In order to build this project these are the essential components that you need:

:-Raspberry pi<BR>
:-TMP102 ( Temperature Sensor)<BR>
:- Jumper wires and breadboard to obtain the i2c address for the sensor on the temporary circuit.<BR>
:- PCB board with final circuit printed on it .<BR>
:- Header pins to attach raspberry pi and the sensor together on PCB.<BR>
:- Case to hold ciruit together and prevent it from damaging.<BR>

 
## TOTAL EXPENCE OF THE PROJECT

Here is the budget of my project by opening the link below you can check the total cost of it and by further clicking on the components such as raspberry pi you can check the website from where I bought each part .
<BR>
  
  
[shubam_budget (2).xlsx](https://github.com/Shubhamsharma1101/TEMPSENS/files/2669488/shubam_budget.2.xlsx)


  <BR>
    
## TIME REQUIRED 
By going through all the instructions and following them carefully and properly you can make the project within a time span of two days . ONCE YOU GET ALL THE PARTS YOU REQUIRE FOR THE PROJECT.
  And if you are pursuing other courses in a school then you need to make a proper schedule so that equal time is given on each and everything . 
  <BR>
  
  Here's what my schedule looks like . (CLICK ON THE LINK BELOW)
  
  <BR>
  
  [schedule.zip](https://github.com/Shubhamsharma1101/TEMPSENS/files/2669568/schedule.zip)
  
  <BR>
 
![capture](https://user-images.githubusercontent.com/43188523/49832975-2c81dd80-fd66-11e8-9e3e-3fffc41aaa28.PNG)
<BR>
  
## MECHANICAL ASSEMBLY
  
## Setup raspberry pi
Once you have got your raspberry pi start working on its functionality download required operating System and allow all the permissions required. 

<BR>
  
## Hardware Setup ON BREADBOARD to check the address.
  
Once you have installed required OS and softwares in your reaspberry pi time to get your hardware ready. starting with connections you have to make sure your sensor is at the right address. In this case required address is Ox4a . 

<BR>

![eed7d23c-5488-4dad-8136-a64f345be486](https://user-images.githubusercontent.com/43188523/47396423-b44d5300-d6f8-11e8-80f6-3aca06775948.jpg)

<BR>
  
Also you can see in the picture there is my i2c address on the rpi terminal. Before it was showing me address (48) instead of (4a) when I connected all my wires and made the connection for RPI terminal connection. Then I added one more wire (IN PICTURE WHITE WIRE) i.e address wire which goes from SDA to ADD0 on the sensor.
<BR>
  
TO OBTAIN ADDRESS USE THE FOLLOWING COMMAND AFTER MAKING THE CONNECTION WITH YOUR RPI.

  
 ## i2cdetect -y 1
 
  
  
    
    
