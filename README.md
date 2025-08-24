# Temperature-logger-using-an-analog-sensor-and-Arduino-Uno
Real-time temperature logger using analog sensor and Arduino Uno. Converts analog voltage to °C and logs via serial monitor. Fully simulated on Wokwi—no hardware required.

This project reads temperature data from an analog sensor (e.g., LM35) and logs it via serial monitor using Arduino Uno. It simulates real-time temperature tracking and conversion from analog voltage to Celsius.

# Live Simulation
Run the project instantly on Wokwi:  
[Click to open simulation](https://wokwi.com/projects/440159173939262465)

# Components Used
- Arduino Uno
- Analog temperature sensor (simulated)
- Serial Monitor (9600 baud)

# How It Works
- Reads analog value from sensor
- Converts voltage to temperature using formula:
  

\[
  \text{Temperature (°C)} = (\text{Voltage} - 0.5) \times 100
  \]


- Displays temperature in °C every second
  
# Future Enhancements
- Add SD card logging
- Display data on LCD
- Add timestamp using RTC module

# Author

Varshitha P
Final Year B.E. in Electronics and Communication  
Kalpataru Institute of Technology, Tiptur  
Focused on sensor systems, automation, and ethical engineering  
GitHub: [@Varshitha26226](https://github.com/Varshitha26226)
