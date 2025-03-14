# Fire Prevention System 🔥

This project is a **Fire Prevention System** designed to detect fire using multiple sensors and trigger appropriate responses. The system integrates various sensors, actuators, and peripheral devices to monitor and mitigate fire hazards effectively.

## Features 🚀
- **Fire Detection**: IR Sensor, Temperature Sensor (MAX6675), and Smoke Gas Sensor (MQ2).
- **Sensor Calibration**: IR sensor calibrated using the Wheatstone Bridge method.
- **Temperature Measurement**: MAX6675 Thermocouple Sensor with SPI communication.
- **Gas Detection**: MQ2 sensor with analog output.
- **Actuators**: Buzzer, Exhaust Fan, and Solar Water Motor for fire control.
- **Peripheral Devices**: LCD Display, ESP32 with GSM900A for SMS alerts.
- **LabVIEW Interface**: Control and monitor the system using LabVIEW.

## Components 🛠️
### Sensors  
- **IR Sensor** (Photo Diode)  
- **MAX6675 Thermocouple Sensor**  
- **MQ2 Smoke Gas Sensor**  

### Actuators  
- **Buzzer**  
- **Exhaust Fan**  
- **Solar Water Motor**  

### Peripheral Devices  
- **LCD Display**  
- **ESP32 with GSM900A for SMS Alerts**  

## Wiring & Pin Configuration 🔌
### Arduino UNO SPI Pins  
| SPI Pin | Arduino UNO Pin |
|---------|----------------|
| SS / CS | 10 |
| MOSI | 11 |
| MISO | 12 |
| SCK | 13 |

## Software Used 💻
- **LabVIEW** for interface and data visualization.
- **Arduino IDE** for programming microcontrollers.

## How to Run 🚦
1. Connect the sensors and actuators as per the wiring diagram.
2. Upload the Arduino code using the **Arduino IDE**.
3. Run the **LabVIEW** program for monitoring and control.
4. Ensure the GSM module is configured to send SMS alerts.

## Future Improvements ✨
- Integration with IoT for remote monitoring.
- AI-based fire prediction model.
- Enhanced sensor fusion for accuracy.

## Contributors 👨‍💻
- Sankavi
- Udith
- Dharshana

## License 📜
This project is licensed under the MIT License.

---
### 🔥 Stay Safe! Fire prevention saves lives.
