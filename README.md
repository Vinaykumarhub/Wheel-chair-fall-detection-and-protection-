# Wheel-chair-fall-detection-and-protection-
its the my final year project work i was done my role in the project it is circuit design and simulation also connection part the circuit design is shown below 👇 
![WhatsApp Image 2025-01-05 at 8 43 37 AM](https://github.com/user-attachments/assets/3583b8a5-1f2d-4678-83dc-071b0836ee30)
in abaove circiut desgin in cirkit desier website in that we create desgin of any arduino iot projects


The circuit diagram illustrates a system designed for wheelchair fall detection using an Arduino Uno microcontroller. The primary components include an accelerometer sensor (ADXL335), a GPS module (NEO 6M), a GSM SIM 900 module, an ESP8266 WiFi module, a buzzer, servo motors (MG996R), and a rechargeable battery for power. Each component is interconnected with the Arduino, and the system is powered using the battery module. The system detects unusual tilts or falls based on accelerometer readings and alerts a caregiver or monitoring system.

### How It Works:
1. **Accelerometer for Fall Detection**: The ADXL335 accelerometer sensor measures the wheelchair's orientation in three axes (X, Y, and Z). If the readings indicate abnormal tilting or falling (exceeding predefined thresholds), it triggers an alert. These readings are sent to the Arduino for processing.
2. **Alert Mechanism**: Once a fall is detected, the Arduino activates a buzzer for an immediate audible alert. Simultaneously, the GSM SIM 900 module sends an SMS alert to predefined emergency contacts, including the location obtained from the GPS module.
3. **Location Tracking**: The GPS NEO 6M module provides the exact geographical coordinates of the wheelchair's position. This data is crucial for rescuers to locate the individual quickly. The location information is sent along with the SMS alert.
4. **Remote Monitoring via WiFi**: The ESP8266 WiFi module enables the system to send fall detection data to a remote server or mobile application for real-time monitoring. This feature ensures caregivers can access updates and take action remotely.
5. **Additional Safety Features**: The servo motors (MG996R) may be used for mechanical adjustments, such as stabilizing the wheelchair or locking it in place after a fall. The rechargeable battery ensures continuous operation without reliance on external power sources.

### Simulation:
To simulate this setup:
1. Connect the components as per the circuit diagram using jumper wires and a breadboard.
2. Upload the Arduino code that handles sensor data, GSM communication, GPS data reading, and WiFi data transmission. The code can be tested with the Arduino IDE.
3. Simulate falls by tilting the accelerometer and observe the buzzer, SMS alerts, and data updates on the remote monitoring platform.
4. Ensure proper power connections from the rechargeable battery and validate each module's functionality individually before integrating the entire system.
5. Test the system in different conditions to confirm accuracy, such as normal wheelchair movement and actual falls. 

Would you like help with the Arduino code or component setup?





