Day 3 (7 sept):
===============
# JULIE EDITING INDEX.MD ONLINE VIA GITHUB

objective :  Introduction to a servo motor and how to control it with a potentiometer. 

Introduction to a DC motor. 

Component list:  Servo motor

Potentiometer 

Arduino

Breadboard 

DC motor

L293D

HandsOn:

First we built a servo motor and coded it to turn 0, 90 and 180 degrees and we could also see the change on the display. 

![](https://lh5.googleusercontent.com/P5hEVp-YlWhw0K-Spb3UuLfHk2DKJfIcaP-7-UaPqY7jGGerHwt9JDV6pD5_4PHCHxnLBVLZRvjC4GQt2MaALJTks37CZs9qOrpReY-b1b5QkkzCR0xpXNhicQq4gwkQXNk0zn4o8pxpFOb5l7fP6zM)

After that we tried to control the servo motor with a potentiometer.

![](https://lh6.googleusercontent.com/qa__57ulGhCjveuhp_ZtFsJWT8OC5sxG-I21wGFasWiyIQr89_DYRCyTpEdfzW7H-bJG9tQu4pOJPXBZVjnlwxFQtmMIQ45jCZoMNrFEENUIJiRdo7o_50_xmVAltBqSboKeeb8NCKZYhdU09yygbpg)

After this we learned about a DC motor and how to control it with a L293D. And the challenge was to work with 2 DC motors. 

![](https://lh6.googleusercontent.com/6f-Jgn_0yL_pDspsd8OWmwFqSDbQQnfOnq6m5D6ZJibk0Hx_OAFnIFOfVxqrXRNNI0rZjq0wgAuXJD-BBHPaJLCHDSjBXbjV5MBdrQzJdZhfPiImU3eucP0aZd_ylepL9DsOkf95HG6fQLdb1JXyocA)

Code:

For the servometer:

#include <Servo.h>

Servo myservo;

int servoPin = 3;

void setup()

{

  myservo.attach(servoPin);

  Serial.begin(9600);

}
