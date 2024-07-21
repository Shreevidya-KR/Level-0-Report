# TASK 10: Speed Control of DC Motor  
In this task we understand the control of DC motors using the L298N motor driver and the Arduino board. Using an UNO and H-Bridge L298N motor driver, control the speed of a 5V motor.  
The components are:  
![components](https://github.com/Asshray-Sudhakar/Marvel-Task-1-Images/blob/main/Components.png?raw=true)  
The connectons are made as shown below:  

**Potentiometer	Arduino UNO**  
Ground-	GND  
Power- 5v  
Central pin-	A0  

**L298N motor driver &**	**Components**  
ENA: ~10 of Arduino UNO  
IN1: 8th Digital pin of Arduino UNO  
IN2: ~9 of Arduino UNO  
GND: -ve of 9 v power supply  
12V: +ve of 9 V power supply  
Output 1:One terminal of DC motor  
Output 2:2nd terminal of DC motor  

*Note*: Here the ENA pin should be compulsorily connected to a PWM (~) pin of the Arduino    

**Working**:  
 In this task I learnt about the speed of a DC motor can be controlled by changing its input voltage. A widely used technique to accomplish this is Pulse Width Modulation (PWM). PWM is a technique in which the average value of the input voltage is adjusted by sending a series of ON-OFF pulses.  This average voltage is proportional to the width of the pulses, which is referred to as the Duty Cycle. The higher the duty cycle, the higher the average voltage applied to the DC motor, resulting in an increase in motor speed. The shorter the duty cycle, the lower the average voltage applied to the DC motor, resulting in a decrease in motor speed.The following are the shots of the working model.  
 ![speed control](https://github.com/Shreevidya-KR/general-task-report/blob/main/speed%20control.jpg?raw=true)   
 
 *Link for  the working model:*  
 https://youtu.be/anoMvMl6f74?feature=shared