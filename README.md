# Wash Buddy
It is basically a timer that can help you wash your hands enough.
But there is a few things that can make you does not feel boring.



### Feature 
* A feature where if you do not wash your hands, the music extends and the remaining time on the LCD does not decrease
* A feature using LED that changes color according to the remaining time 
* A feature that detects hands and dispenses soap from the dispenser
* A feature that displays status on the LCD
* A feature that gives a thumbs up when handwashing is complete
* A feature that uses an ON/OFF switch to turn the power on and off



### Working system
User Recognition
When a user is detected using an ultrasonic sensor, the system dispenses soap using two Servo motor and starts the service with playing the music using piezo.

Handwashing Recognition
Each time the hand moves, the output value of the ultrasonic sensor changes, which allows the system to determine whether the user is properly washing their hands.

Sound Feedback
If the output value of the ultrasonic sensor changes little over the next 30 seconds, the music extends and the remaining time on the LCD does not decrease.

Visual Feedback
The color of the LED changes and the remaining time updates on the LCD according to the remaining time. If the user does not wash their hands thoroughly,
the remaining time does not decrease, the LED color does not change, and the music extends. 

