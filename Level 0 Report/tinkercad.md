# TASK 9: Tinkercad  
In this task, I designed a simple circuit to estimate the distance between the ultrasonic sensor and the object.The components required are:  
![components](https://github.com/Asshray-Sudhakar/Marvel-Task-1-Images/blob/main/Components%20needed.png?raw=true)
The connections made are as follows:

**Ultrasonic Sensor	Arduino UNO** 
VCC  	5v  
TRIG	Pin 8  
ECHO	Pin 9  
GND 	GND  
**P.S**: Here the Pins 8,9 & 3 are Digital PWM pins on the Arduino.  
**LCD (16x2) 12C Arduino UNO**  
VCC	5v  
SDA	Blank pin  
SCL	Blank pin  
GND	GND  
**Servo Motor	Arduino UNO**
Ground	GND  
Power	5V  
Signal	Pin 3  
The circuit looks as shown below:
![tinkercad](https://github.com/Shreevidya-KR/general-task-report/blob/main/tinker.jpg?raw=true)
Working principle:  
The term "ultrasonic" refers to frequencies higher than 20 kHz, which are inaudible to humans because they exceed the upper limit of the human hearing range. Ultrasonic sensors typically have two cylindrical components protruding outward: a transmitter (T) and a receiver (R). The transmitter emits ultrasonic sound waves, which interact with an object in front of the sensor and reflect back to the receiver.
The distance between the ultrasonic sensor and the object is calculated based on the time it takes for the reflected ultrasonic wave to reach the receiver.



