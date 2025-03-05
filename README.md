# GSM-based pH Monitoring System

## Overview
This project is a **pH monitoring system** that uses a **GSM module (SIM900D) and a pH sensor** to measure water quality. If the pH value deviates from the safe range (6.8 - 7.2), the system will send an **SMS alert** to the owner, enabling timely action to protect fish and maintain optimal water conditions.

## How It Works
1. **pH Sensor** measures the water condition.
2. If the pH goes beyond **6.8 - 7.2**, the system detects an issue.
3. **SIM900D GSM Module** sends an SMS to the owner:
   - **Message:** `"pH value is not good"`
4. The owner gets notified and can take corrective action.

## Hardware Components
- **pH Sensor** – Measures water pH.
- **SIM900D GSM Module** – Sends SMS alerts.
- **Microcontroller (Arduino, ESP, etc.)** – Processes data and controls the GSM module.

## Pin Configuration
### **SIM900D GSM Module**
- **TXD** – Transmit data (Connect to RXD of the microcontroller)
- **RXD** – Receive data (Connect to TXD of the microcontroller)
- **GND** – Ground

### **pH Sensor**
- **GND** – Analog Ground
- **GND** – Supply Ground
- **VCC** – 5V DC

## Technical Specifications
### **SIM900D GSM Module**
- Maximum Voltage: **5V**
- Maximum Current: **2A**
- Auto-adapts to **3.3V and 5V** main boards
- Dimensions: **67mm x 85mm x 21mm**
- Weight: **35.7g**

### **pH Sensor**
- Maximum Voltage: **5V**
- Maximum Current: **10mA**
- Weight: **25g**
- Service Life: **3 years**

## Future Enhancements
- Add data logging for pH values.
- Use an IoT platform for remote monitoring.
- Implement automatic pH correction mechanisms.


