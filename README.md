# Power-Meter-PZEM-004T
The PZEM-004T sensor is a sensor that can measure current, voltage, power and energy from AC power. This sensor outputs by serial communication. If we want to connect with Arduino, the communication used is serial communication. This tool is connected to the sim800l module, so that data from the PZEM-004T sensor can be sent to the IoT Thingspeak platform using the HTTP request method.

# Hardware
- Arduino Uno / Nano (ATmega 328)
- Module SIM800L (Ver.1 / Ver.2)
- Module StepDown LM2596 ( Only For Use SIM800L Ver.1)
- Module Pzem-004t

# Software
- Arduino IDE
- AT Command Tester

# Datasheet
- Arduino Uno 
- ![image](https://user-images.githubusercontent.com/50385294/126890164-56fe7eca-7e9a-4d83-9675-08d0107678a6.png)
- SIM800L Ver.1 
- ![image](https://user-images.githubusercontent.com/50385294/126890194-f4322bc4-2058-4870-87b9-a2147abc8d3d.png)
- PZEM-004T
-  ![image](https://user-images.githubusercontent.com/50385294/126890246-eda6d228-e809-43b7-96e7-61e480faf3fb.png)

# Diagram Wiring
![Pzem-004t sim800](https://user-images.githubusercontent.com/50385294/126891100-62b728db-8caf-4683-a290-3ea63b6ba4f5.png)

# Documentation
- Thingspeak
![Screenshot (94)](https://user-images.githubusercontent.com/50385294/126891117-2b170dfc-6506-40bb-9577-61f3a128300a.png)
![Screenshot (95)](https://user-images.githubusercontent.com/50385294/126891118-973eba16-58e3-4b2c-b4ed-bf428a2e94f1.png)
- https://thingspeak.com/channels/1305587








