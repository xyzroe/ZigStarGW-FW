# ZigStar LAN Gateway - Firmware
Firmware for [ZigStar LAN Gateway](https://github.com/mercenaruss/zigstar_gateways).
For more documentation visit [zig-star.com](https://zig-star.com).

![](https://github.com/mercenaruss/zigstar_gateways/raw/main/img/Default.png)

# Functions
- Zigbee UART port forwarding using LAN socket connection
- MQTT connection to view ESP32 status. 
- Restarting Zigbee and enabling Zigbee BSL via webpage and MQTT
- ESP32 firmware update via webpage
- Automatic switching to Wi-Fi network when RJ45 is disconnected - "Emergency mode"
- If no Wi-Fi network is available, the hotspot will be configured


![](https://github.com/xyzroe/ZigStarGW-FW/raw/main/images/main_eth.png)  

![](https://github.com/xyzroe/ZigStarGW-FW/raw/main/images/main_emergency_mode.png)  

![](https://github.com/xyzroe/ZigStarGW-FW/raw/main/images/logs.png)  

![](https://github.com/xyzroe/ZigStarGW-FW/raw/main/images/update.png)  



Base code was taken from [ZiGate-Ethernet](https://github.com/fairecasoimeme/ZiGate-Ethernet)  

Some ideas and code snippets was taken from [esp-rfid](https://github.com/esprfid/esp-rfid)
