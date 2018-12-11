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
 <BR>

If you didn't get the same ADDRESS, there is something worng with your circuit check the connections properly.

## PCB AND SOLDERING
<BR>
Now that you know how to connect your sensor to raspberry pi you can start working on PCB that is to bring circuit that you made on a board permanently. For that you have to carefully design your PCB using software called Fritzing which will help you to design your PCB.
 The wires that are yellow in colour are on the top side of the board and orange ones are at the bottom of the PCB . It should look like this:<BR>
  
  <BR>
  
    
![pcbcircuitboard_pcb](https://user-images.githubusercontent.com/43188523/47758173-33ee9b00-dc80-11e8-936f-78660a1faa6a.png)

<BR>
  
Next step is to get your PCB board made once you have got your PCB  solder the socket headers to the PCB. Be carefull while soldering the PCB use the safety glasses while doing it.

<BR>
  
![pcb design](https://user-images.githubusercontent.com/43188523/48296731-7f672d00-e468-11e8-8140-c19316ed11c4.jpg)
<BR>
  
 After that you can just attached your PCB with sensor mounted on it to the raspberry pi . Make sure all the wires for the raspberry are connected and your sensor is at the correct address.

![img_6730](https://user-images.githubusercontent.com/43188523/48526380-78b82b80-e855-11e8-8536-2ad221079ebd.PNG)
<BR>
  
  ## OBTAINING THE READINGS
  
  HERE'S THE LINK FOR MY CODE
  
   https://learn.sparkfun.com/tutorials/python-programming-tutorial-getting-started-with-the-raspberry-pi/experiment-4-i2c-temperature-sensor
  
  <BR>
  
  If all the instructions are followed carefully and step by step as shown in the link then you should be able to detect your readings for the sensor.<BR>
  
  
   ![tmp102](https://user-images.githubusercontent.com/43188523/48526197-c7b19100-e854-11e8-8d53-9bb89da56d6a.png)
   
   <BR>

Then I rubbed my hand and covered the sensor with my fingers and it was showing change in temperature.Also on blowing air from the mouth it shows a change in the readings.


<BR>
  
  ## ENCLOSURE
  
  All my parts are enclosed properly, easily accessible and securely attached.
  <BR>
  
  ![blog](https://user-images.githubusercontent.com/43188523/48808375-9fabad00-ecee-11e8-82d1-0e6198d2120d.PNG)



  
  
    
    
