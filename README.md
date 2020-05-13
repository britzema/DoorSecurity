# DoorSecurity
### A raspberry pi IoT project. 
Simulates a door security system, including an automated porch light, door lock, and doorbell. Porch light is triggered after sensing motion; the doorbell causes the camera to take a picture and send the resulting image to provided email address(es). Door lock status can be controlled via SignalMotor.py (can be run from anywhere); the two programs are linked through MQTT. Once unlocked, door automatically locks after 10 seconds.
Built by Brad Ritzema and Zach Chin
