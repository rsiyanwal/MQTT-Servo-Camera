# MQTT-Servo-Camera
We can rotate the servo motor with the help of a message received via MQTT. For instance, if we receive "left" in the message, we can rotate the motor to the left. Similarly, if we receive "right", we can rotate the motor to the right. This mechanism can be utilized in scenarios where we want to take pictures in a specific direction. For example, we can attach a camera to the servo motor and rotate it towards the direction we want to capture the image, then trigger the camera to capture the image and send it via MQTT to the desired destination.

For this experiment, we have used Raspberry Pi 4B. 
