# temperature-monitoring-system

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: NAMITHA.J.B

*INTERN ID*: CT04DZ84

*DOMAIN*: EMBEDDED SYSTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH


**The Temperature Monitoring System is an embedded electronics project designed to read ambient temperature using a temperature sensor and display the real-time temperature on a 16x2 LCD screen. This project fulfills the requirements of Task 3 of the CODTECH Internship, where the goal is to use a sensor-based approach to measure temperature and output the results either on a serial monitor or an LCD. In this implementation, an LCD display is used to provide a standalone system for live temperature monitoring without the need for a computer.

The system utilizes an Arduino Uno microcontroller, a TMP36 (or LM35) temperature sensor, and a 16x2 character LCD. The temperature sensor outputs an analog voltage that varies based on the surrounding temperature. This voltage is read using the analog input pin A0 on the Arduino. The Arduino then converts the analog reading into a digital temperature value using a mathematical formula. For TMP36, the formula used is temperature = (voltage - 0.5) * 100, where voltage is calculated from the analog reading.

The LCD module is connected to the Arduino through six digital pins (RS, E, D4-D7), and a 10kΩ potentiometer is used to adjust the contrast of the LCD screen. The LCD is initialized using the LiquidCrystal library, and the temperature is updated every second to reflect the current reading from the sensor. The LCD shows the temperature in degrees Celsius, formatted neatly on the screen.

This system provides a simple yet effective way to continuously monitor temperature in real-time. It can be used in small-scale applications such as room temperature monitoring, greenhouse automation, server room maintenance, or even as a learning project for students beginning to explore electronics and embedded systems.

The circuit is built using a breadboard, making it easy to prototype and modify. The LCD is powered with 5V from the Arduino, and the data lines are connected to digital pins 12, 11, 5, 4, 3, and 2. The temperature sensor is powered using 5V and GND, and its output is fed to the analog input A0.

One of the strengths of this project is its simplicity and versatility. By changing the code slightly, users can display the temperature in Fahrenheit, log data to an SD card, or send data via Bluetooth or Wi-Fi for remote monitoring. This makes it a great foundation for IoT-based applications.

In conclusion, this project successfully demonstrates how an Arduino can be used to create a practical and interactive temperature monitoring system using a sensor and LCD display. It showcases skills in sensor interfacing, analog-to-digital conversion, and LCD programming. The deliverables of this project include the complete circuit design, Arduino code, and output demonstration via simulation or real-time testing, making it a well-rounded embedded systems project for internship evaluation.

*OUTPRT*

<img width="1366" height="546" alt="Image" src="https://github.com/user-attachments/assets/4ef63594-e983-49b6-b2c2-003797184ce9" />


