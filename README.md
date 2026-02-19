This study aims to develop a solar monitoring system using IoT for optimization of energy prediction, planning, production, and consumption.

The objectives of the study are to;

i. Design an IoT architecture.
 
 
ii. Develop a real-time data acquisition system.
iii. Implement IoT architecture and create a user interface.
iv. Evaluate the performance of the IoT based monitoring systems.
 

The implementation of the IoT-based solar monitoring system successfully produced a functional prototype capable of capturing, processing, and displaying real-time solar panel performance data. Key parameters such as voltage, current, power output, temperature, and light intensity were continuously monitored using the integrated INA219, DHT22, and BH1750 sensors. These values were then transmitted via the ESP32’s Wi-Fi module and presented on a locally hosted dashboard. The dashboard displayed the data in an intuitive format, including charts, numerical values, and performance alerts, making it simple for non-technical users to interpret system health. A log file was also generated and stored in the ESP32’s SPIFFS memory, enabling historical performance analysis and export as CSV for offline review.

The system provided adaptive insights into solar panel performance by correlating environmental conditions with power output, allowing the detection of potential inefficiencies such as dust accumulation or temperature-related performance drops. The visualization component ensured that data was not only presented in real time but also contextualized through performance metrics and health bars. These results confirmed the ability of the developed system to bridge the gap between raw sensor data and actionable insights for solar panel maintenance. Overall, the implementation demonstrated that low-cost IoT technologies could be effectively applied in renewable energy monitoring with significant practical utility.