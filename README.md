# -Smart_traffic_management_System
Project_on_IOT_and_EmbeddedSystem

* Automated Traffic Density Detection System
This project aims to automate traffic density detection and optimize traffic signal timing using ultrasonic sensors, servo motors, and RGB LEDs, offering a smart solution for traffic management in urban areas.

🔑 Key Features
✅ Real-time vehicle detection using ultrasonic sensors
✅ Traffic density calculation with dynamic signal control
✅ LCD display showing traffic alerts
✅ RGB LED-based traffic signal system
✅ Automated loop for continuous monitoring

🛠️ Technologies Used
Arduino Uno
Ultrasonic Sensor (HC-SR04)
Servo Motor
RGB LED
LCD Display (16x2)


📌 Working Process
1.System Initialization

2.Initialize LCD, Servo Motor, Ultrasonic Sensor, and RGB LED.
3.Set initial traffic detection parameters.
4.Vehicle Scanning
5.Servo motor rotates at angles (50°, 90°, 130°).
6.Ultrasonic sensor detects vehicles based on distance.
7.Detected vehicles are counted to calculate traffic density.
8.Traffic Density Calculation
  High Traffic (> 60%) → "Traffic Ahead" on LCD, longer green light duration.
  Low Traffic → "Clear Route" on LCD, normal signal flow.
9.Signal Control
  RGB LED controls traffic lights dynamically.
  Green signal duration adjusts based on traffic density.
10.Continuous Monitoring

-The system repeats scanning and traffic control automatically.

🎯 Applications
Smart Traffic Management
Urban Traffic Systems


📌 How to Run
Install Arduino IDE.
Upload the code to Arduino Uno.
Connect components as per circuit .
Power the system and observe real-time traffic updates.

📷 Output
LCD displays traffic status.
LEDs change color based on traffic density.
Serial Monitor logs traffic updates.

⭐ Give this project a star if you like it!






