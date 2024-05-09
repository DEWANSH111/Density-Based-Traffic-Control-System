# DENSITY BASED TRAFFIC CONTROL SYSTEM
The project is aimed at designing a density based dynamic traffic signal system where the timing of signal will change automatically on sensing the traffic density at any junction. Traffic congestion is a severe problem in most cities across the world and therefore it is time to shift more manual mode or fixed timer mode to an automated system with decision making capabilities. Present day traffic signaling system is fixed time based which may render inefficient if one lane is operational than the others. 

To optimize this problem we have made a framework for an intelligent traffic control system. Sometimes higher traffic density at one side of the junction demands longer green time as compared to standard allotted time . 
We, therefore propose here a mechanism in which the time period of green light and red light is assigned on the basis of the density of the traffic present at that time. This is achieved by using PIR (proximity Infrared 
sensors). Once the density is calculated, the glowing time of green light is assigned by the help of the microcontroller (Arduino). 

The sensors which are present on sides of the road will detect the presence of the vehicles and sends the information to the microcontroller (Arduino) where it will decide how long a flank will be open or when to change over the signal lights. 

The main purpose of this project is, if there will be no traffic on the other signal, one shouldn’t wait for that signal. The system will skip that signal and will move on the next one.
