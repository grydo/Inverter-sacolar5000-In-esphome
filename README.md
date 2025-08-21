# Inverter sacolar-5000 In esphome
ESPHome component to monitor a inverter sacolar5000 (clone growatt) via UART-TTL, reading inverter sacolar5000 data into Home Assistant via the modbus using a TTL to RS485 module and a ESP32. This setup completely eliminates the need to collect data via the cloud. Also, it is possible to increase the update frequency of the data. My sensors are updating every 15 sec.
Link ttl used  https://amzn.eu/d/5ZO1Ku5
# Installation
1.Create your esp32 in esphome in home assistant         
2.Upload the your basis config via. usb from pc.  
3.Test wireless upload  
4.Copy all content (make sure you have your wifi ssid&password in the secrets)  
5.Edit the sensors in the config if you like  
5.Upload wireless or USB  
# Wiring of generic esp32 or esp8266 & TTL module
RX / TX between esp and ttl converter may have to be swapped. This seems to be a little different from espboard to espboard. If it dosent communicate(RX/TX led both blinking) Try swap rx/tx on the esp.
![wiring](https://github.com/user-attachments/assets/d422b9d4-b6b2-4ec9-af89-3e231c52aab1)
![ttl-esp32](https://github.com/user-attachments/assets/2435bb75-6c80-41e5-b26e-0959e91eb0eb)

