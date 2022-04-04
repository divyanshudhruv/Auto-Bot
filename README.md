

# **Auto Bot**

<br>

😉 A Simple Yet Powerful Robot Based On **Python** And **Arduino** !

<br>

## Team:

> Divyanshu Dhruv

> Kinshuk Kathuria

> Saksham Jain

> Ishan Kher

<br>

## Items:

> **Arduino Uno**
 
>  Motor Driver
 
>  TT Gears

>  Wheels (4x)
  
>  Servo Motor

>  Ultrasonic Sensor

>  18650 Li-on Battery (2x)

>  18650 Battery Holder

>  Male and Female Jumper wire

>  Engineered  Wood (MDF)

>  DC Power Switch

<br>



## Contribute:

> Just A Sample Text !

<br>

## Logo:

> We Are Finding A Good Logo.

<br>

## Logo:

> We Are Finding A Good Logo.

<br>

## TODO:

> - [x] Discussion
> 
> - [ ] Make Prototype
> 
> - [ ] Final Project

<br>

## Note:
```ino

//ARDUINO OBSTACLE AVOIDING CAR//

#include <AFMotor.h>  
#include <NewPing.h>
#include <Servo.h> 



void setup() {

  myservo.attach(10);  
  myservo.write(115); 
  delay(2000);
  distance = readPing();
  delay(100);
  distance = readPing();
  delay(100);
  distance = readPing();
  delay(100);
  distance = readPing();
  delay(100);
}


```
