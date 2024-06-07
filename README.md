# Smart-Water-Meter

## Overview
Welcome to the Smart Water Meter and Automated Irrigation System repository! This project leverages cloud technology and IoT to provide an advanced solution for efficient water management in agriculture. By integrating real-time leak detection and automated irrigation, our system has demonstrated a remarkable 40% increase in crop yields.

## Features
- **Smart Water Meter**: Monitors water usage in real-time.  
- **Automated Irrigation System**: Adjusts water delivery based on soil moisture and environmental conditions.  
- **Real-Time Leak Detection**: Identifies and alerts about leaks to prevent water wastage.  
- **Cloud Integration**: Stores and processes data for advanced analytics and reporting.  
- **IoT Connectivity**: Seamlessly connects sensors and actuators for optimal performance.
## Benefits
- **Increased Crop Yields**: Achieve up to 40% higher yields through optimized water usage.
- **Water Conservation**: Prevent water wastage with real-time leak detection.
- **Cost Efficiency**: Reduce water and energy costs with automated, precise irrigation.
- **Sustainability**: Promote sustainable agricultural practices through smart technology.
## Hardware Requirements
- **ESP32 or ESP8266 microcontroller**
- **DHT22 sensor (for temperature and humidity)**
- **Flow sensor**
- **pH sensor**
- **Turbidity sensor**
- **Soil moisture sensors (digital and analog)**
- **Relay module (for pump control)**
- **WiFi connection**
- **Blynk app (for remote monitoring and control)**
- **ThingSpeak account (for data storage and visualization)**
- **Telegram bot (for leak detection notifications)**

## Software Requirements
- **Arduino IDE**
- **Blynk library**
- **ThingSpeak library**
- **UniversalTelegramBot library**
- **WiFi library for ESP32 or ESP8266**

## Installation

To get started with the Smart Water Meter and Automated Irrigation System, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DMadhumita2904/Smart-Water-Meter/edit/main/README.md

2. **Navigate to the project directory**:
    ```bash
    cd smart-water-meter

3. **Open the project in Arduino IDE**:
   ```bash
   arduino SmartWaterMeter.ino
4. **Install required libraries**:
   - **Blynk**
   - **ThingSpeak**
   - **UniversalTelegramBot**
   - **DHT sensor library**
5. **Configure your credentials and settings**:
   - Replace **BLYNK_TEMPLATE_ID** , **BLYNK_TEMPLATE_NAME** , and **BLYNK_AUTH_TOKEN** with your Blynk project details.
   - Replace **ssid** and **pass** with your WiFi network credentials.
   - Replace **ch_no** and **write_api** with your ThingSpeak channel number and API key.
   - Replace **BOTtoken** and **CHAT_ID** with your Telegram bot token and chat ID.
6. **Upload the code to your microcontroller**:
    - Select the appropriate board and port from the Arduino IDE.
    - Click on the upload button to flash the code onto the microcontroller.
  
## Usage
- **Deploy sensors and actuators**: Place water meters, soil moisture sensors, and irrigation valves in the field.
- **Configure the system**: Adjust settings via the Blynk app to match your specific agricultural needs.
- **Monitor and manage**: Use the real-time dashboard in the Blynk app to track water usage, soil moisture levels, and system alerts.
- **Analyze data**: Access historical data and analytics on ThingSpeak to make informed decisions about water management.
## Code Description
The code integrates various sensors and modules to monitor and control the irrigation system:

- **WiFi and Blynk setup**: Connects the microcontroller to WiFi and initializes Blynk for remote monitoring.
- **ThingSpeak setup**: Sends sensor data to ThingSpeak for storage and visualization.
- **Telegram bot setup**: Sends notifications about leak detection to the user via Telegram.
- **Sensor readings**: Collects data from flow, pH, turbidity, soil moisture, and DHT22 sensors.
- **Leak detection**: Monitors for leaks and sends alerts if detected.
- **Automated irrigation**: Controls the pump based on soil moisture levels.

## Contributing
We welcome contributions to enhance and improve the Smart Water Meter and Automated Irrigation System. Please follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-branch
3. **Make your changes and commit them**:
   ```bash
   git commit -m "Add your message"
4. **Push to the branch**:
   ```bash
   git push origin feature-branch
5. **Create a pull request**.

## License
**This project is licensed under the MIT License.**

## Acknowledgements
**We would like to thank all contributors and the open-source community for their invaluable support and collaboration.**

## Contact
**For questions or support, please open an issue in this repository or contact us at krishnamadhumitadutta@gmail.com**.




