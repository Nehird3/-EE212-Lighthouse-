# -EE212-Lighthouse-
This is a project for the lesson EE212 Microprocessors with Assembly/C coding languages
This project was done using a servo, ultrasonic sensor, a buzzer, a joystick and interrupts.
This project is basically lighthouse. There is a 2 mode in the code. First part, lighthouse 180 degrees around its axis by controlling joystick. There are 2 lasers positioned opposite each other on the lighthouse to scan its entire surroundings. In this way, the lighthouse can scan 360 degrees.
Second part, The ultrasonic sensor on the lighthouse first turns 180, then the lighthouse turns 180 degrees around itself. In this way, it provides a 360-degree automatic scanning. If the sensor sees an object, the buzzer beeps and the laser stays on the object. The buzzer beeps as long as the sensor sees the object. When the object moves away, the lighthouse continues to scan from where it left off.
