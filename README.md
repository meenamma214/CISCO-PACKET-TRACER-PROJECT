# Room Automation System (IoT using Cisco Packet Tracer)

## Project Overview
This project demonstrates a Room Automation System built using Cisco Packet Tracer IoT devices.  
The system integrates multiple smart devices such as a Motion Detector, Home Gateway, Light, Fan, Tablet PC, Temperature Monitor, and Heating Element.  
The goal is to automate room functions like lighting, temperature regulation, and fan control to create a smart and energy-efficient environment.

## Objectives
- Automate lighting based on motion detection.  
- Regulate temperature using a Temperature Monitor and Heating Element.  
- Control devices remotely via a Tablet PC connected to the Home Gateway.  
- Provide a scalable and user-friendly IoT setup for smart homes.

## Components Used
- Home Gateway → central hub to connect and manage IoT devices  
- Tablet PC → user interface for controlling devices  
- Motion Detector → detects movement in the room and triggers automation  
- Light → turns ON/OFF based on motion rules  
- Fan → maintains airflow when required  
- Temperature Monitor → monitors ambient temperature  
- Heating Element → activated when temperature drops below set threshold  

## Working Logic
- If Motion Detector detects movement → Light turns ON.  
- If no motion detected for a period → Light turns OFF.  
- If Temperature < 20°C → Heating Element turns ON.  
- If Temperature > 28°C → Fan turns ON.  
- All devices can also be controlled manually via Tablet PC.  

## How to Run
1. Open the project file (`Room_Automation.pkt`) in Cisco Packet Tracer 8.2+.  
2. Ensure IoT devices are connected to the Home Gateway.  
3. Use the Tablet PC → Home Gateway Interface to log in and control devices.  
4. Test the automation:  
   - Move the Motion Detector simulation bar to trigger the Light.  
   - Adjust the Temperature Monitor values to trigger Fan/Heating Element.  

