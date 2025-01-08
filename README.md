<!-- Centered Heading -->
<h1 align="center">Smart SyncEdge Platform</h1>

The **Smart SyncEdge Platform** is an IoT-based home automation system using ESP32. It enables appliance control through physical switches, Google Home, and Arduino Cloud while providing real-time temperature and humidity monitoring with a DHT11 sensor.

## Features  
- **Multi-Interface Control**: Control appliances via physical switches, Google Home app, and Arduino Cloud platform.  
- **Sensor Integration**: Includes DHT11 for temperature and humidity monitoring.  
- **Synchronized Management**: Ensures appliance state is updated across all interfaces.  
- **Wi-Fi Connectivity**: Remote operation and seamless updates.  

## Technologies Used  
- **Microcontroller**: ESP32  
- **Sensors**: DHT11 for temperature and humidity  
- **Control Interfaces**: Physical switches, Google Home, Arduino IoT Cloud  
- **Programming Language**: C++  

## How It Works  
1. The ESP32 connects to a Wi-Fi network for remote control.  
2. Physical switches and relays control up to four appliances.  
3. The DHT11 sensor monitors temperature and humidity.  
4. Appliance states are synchronized across Google Home, Arduino Cloud, and switches.  

## Setup Instructions  
1. Clone the repository to your local machine.  
2. Update the Wi-Fi credentials and device keys in the code.  
3. Upload the code to your ESP32 using Arduino IDE.  
4. Connect the ESP32 to relays and DHT11 as per the wiring diagram.  
5. Use Google Home or Arduino Cloud for remote control.  

## Circuit Diagram  
![first1](https://github.com/user-attachments/assets/ae337b0c-5f2d-4e94-a68b-08fdf3b8cf4a)
