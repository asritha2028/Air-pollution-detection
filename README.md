# Air-pollution-detection
Air_pollution_detection_and_auto_purification
Introduction :
Air pollution is one of the major environmental problems affecting human health and living conditions. Harmful gases such as carbon monoxide (CO) and other pollutants can reduce air quality and cause respiratory and other health problems. This project, Air Pollution Detection and Automatic Purification with IoT Integration, is designed to monitor air quality using gas sensors and automatically activate a purification mechanism when pollution is detected.
The system uses the MQ-135 sensor to monitor general air quality and the MQ-7 sensor to detect carbon monoxide. LEDs indicate the air quality condition, while a fan automatically turns ON for 5 seconds when the system detects a high CO level. ThingSpeak is used as a cloud platform to visualize air quality data before and after purification. Activated carbon sheets can also be incorporated to help adsorb certain harmful gases and improve purification efficiency.

Objectives :
- To detect air pollution using MQ-135 and MQ-7 gas sensors.
- To monitor carbon monoxide levels in the surrounding environment.
- To provide visual indication of air quality using LEDs.
- To automatically activate a fan when pollution is detected.
- To monitor and visualize air quality data using the ThingSpeak cloud platform.
- To compare air quality readings before and after purification.
- To explore the use of activated carbon sheets for gas adsorption.
<img width="1312" height="912" alt="air pollution" src="https://github.com/user-attachments/assets/8211b28b-8fc7-4dea-9524-b6aea16f30ea" />

- Working principle :
1. The MQ-135 and MQ-7 sensors continuously sense the surrounding air.
2. The Arduino UNO reads the sensor values and compares them with predefined threshold levels.
3. Under normal air conditions, the green LED glows.
4. When carbon monoxide or pollution exceeds the defined threshold, the red LED turns ON.
5. The Arduino activates the relay, which switches ON the fan for 5 seconds.
6. Air is circulated through or near the purification arrangement, where activated carbon sheets can help adsorb certain pollutants.
7. Sensor readings are transmitted through the ESP-01 Wi-Fi module to ThingSpeak.
8. The ThingSpeak dashboard displays the air quality data, allowing comparison between readings before and after the purification process.
   
 Advantages :
- Automatic detection of air pollution.
- Real-time monitoring of air quality.
- Automatic fan activation without manual intervention.
- Visual indication using red and green LEDs.
- IoT-based remote monitoring through ThingSpeak.
- Cloud-based storage and graphical representation of sensor data.
- Low-cost and simple prototype design.
- Expandable system with additional sensors and purification methods.
- Activated carbon can improve the adsorption of certain gases and pollutants

Conclusion :
The Air Pollution Detection and Automatic Purification with IoT Integration project provides a simple and effective approach to monitoring air quality and responding automatically to pollution conditions. By integrating MQ-135 and MQ-7 gas sensors with Arduino UNO, the system detects changes in air quality, indicates pollution through LEDs, and activates a fan for 5 seconds when carbon monoxide is detected above the predefined threshold. The ESP-01 Wi-Fi module enables sensor data transmission to the ThingSpeak cloud platform, where readings before and after purification can be monitored and compared. The addition of activated carbon sheets can further improve the purification process by adsorbing certain harmful gases. Overall, this project provides practical experience in sensor interfacing, embedded systems, IoT connectivity, cloud monitoring, and automatic control, while demonstrating the potential of smart systems for improving indoor air-quality awareness.
