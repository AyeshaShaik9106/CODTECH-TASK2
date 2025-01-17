Name:SHAIK AYESHA

Company: CODTECH IT SOLUTIONS

ID: CT4ES4139

Domain: Embedded Systems

Duration: July to August 2024

Mentor: Muzammil Ahmed
![image](https://github.com/AyeshaShaik9106/CODTECH-TASK2/assets/174710469/46610f46-6fbd-4923-8f8f-1eea61c79b55)
![image](https://github.com/AyeshaShaik9106/CODTECH-TASK2/assets/174710469/aa0c861b-bb56-49fe-9464-ab58941ee37f)
![image](https://github.com/AyeshaShaik9106/CODTECH-TASK2/assets/174710469/a82b247b-47a4-4ace-9382-458afc09b9c6)
![image](https://github.com/AyeshaShaik9106/CODTECH-TASK2/assets/174710469/e6a75af7-5293-4424-9c85-42b552ef6437)




**OVERVIEW OF THE PROJECT**

**Project:Temperature and Humidity Monitoring with DHT Sensor**

**Objective:**
-->This project aims to interface a DHT sensor with an Arduino to measure temperature and humidity and display the readings on an LCD screen or serial monitor.

**Components:**

-->Arduino Board: Any Arduino board like Uno, Mega, Nano, etc.
-->DHT Sensor: DHT11 or DHT22 for measuring temperature and humidity.
-->LCD Screen: 16x2 LCD (optional) for displaying the readings.
-->Resistor: 10kΩ resistor (if required for the DHT sensor).
-->Breadboard and Jumper Wires: For making connections.

**Concepts Covered:**

-->Sensor Interfacing: Connecting and reading data from the DHT sensor.
-->Data Display: Displaying sensor data on an LCD or serial monitor.
-->Libraries: Using external libraries for the DHT sensor and LCD.

**Detailed Steps:**
1.Hardware Connection:

-->DHT Sensor: Connect the VCC pin to the 5V pin on the Arduino, the GND pin to the ground (GND) on the Arduino, and the data pin to digital pin 2 on the Arduino.
-->LCD Screen: Connect the pins of the LCD to the appropriate digital pins on the Arduino (pins 12, 11, 5, 4, 3, 2 as per the code). If using an I2C LCD, connect the SDA and SCL pins to the corresponding pins on the Arduino.
-->Resistor: Place a 10kΩ pull-up resistor between the VCC and data pin of the DHT sensor if needed.
2.Software Setup:

-->Libraries: Install the DHT and LiquidCrystal (or LiquidCrystal_I2C for I2C LCD) libraries from the Arduino Library Manager.
-->Code: Write the Arduino code to read temperature and humidity data from the DHT sensor and display it on the serial monitor or LCD screen.

**Educational Value:**
-->Basic Programming: Learn how to write and structure Arduino programs.
-->Sensor Interfacing: Understand how to connect and read data from sensors.
-->Data Display: Learn to display data on different output devices like serial monitors and LCD screens.
-->Libraries: Utilize Arduino libraries for simplifying code and enhancing functionality.


This project serves as a foundation for more advanced projects involving multiple sensors and more complex data processing. It provides practical experience with embedded systems and microcontroller programming.
