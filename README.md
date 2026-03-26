# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1919" height="1199" alt="564213149-3a5f7222-1a86-4773-aa01-0a32d5834270" src="https://github.com/user-attachments/assets/3dc5d4ef-773a-4790-842d-ab7ab35d243c" />

### 2. Network Server – Recent Events
![e34d43d7-f980-46ad-8a47-c89d4091dd2b](https://github.com/user-attachments/assets/b7fee9af-21dd-4fcf-97ba-2969e97509f7)
![ebc13ac5-121d-4bbb-a5dd-23c74c09e8cc](https://github.com/user-attachments/assets/23df7597-affd-4d92-85dc-664b1568c6e9)


### 3. Dashboard Command Sending
<img width="1919" height="1172" alt="Screenshot 2026-02-24 135058" src="https://github.com/user-attachments/assets/8c19b0ad-b4d9-4159-a138-d32ed7cbee3d" />
<img width="1917" height="1168" alt="Screenshot 2026-02-24 135040" src="https://github.com/user-attachments/assets/7323bb87-f8a0-4adc-895e-555ce790f43e" />
<img width="1914" height="1167" alt="Screenshot 2026-02-24 135025" src="https://github.com/user-attachments/assets/5dea07de-c845-48a9-912e-b1269c7bf59c" />
<img width="1919" height="1169" alt="Screenshot 2026-02-24 135014" src="https://github.com/user-attachments/assets/2bfeb484-9390-44b5-840d-85d6e1aedf31" />
<img width="1919" height="1198" alt="Screenshot 2026-02-24 134957" src="https://github.com/user-attachments/assets/588a439f-f941-4ae0-bb3b-38831d7bcce3" />
<img width="1919" height="1168" alt="Screenshot 2026-02-24 135118" src="https://github.com/user-attachments/assets/f31c5e82-36a0-45c8-bc97-66c0a84a30bd" />
<img width="1919" height="1173" alt="Screenshot 2026-02-24 135131" src="https://github.com/user-attachments/assets/23a3285d-255e-4d60-906e-67835fecf984" />


### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![70bd1fe6-aaae-4cc6-aaed-8dcb33865cb3](https://github.com/user-attachments/assets/8cc3e072-0331-4ce2-a0ad-f6afbeba63f0)
### Bulb OFF → Relay OFF
![6ac82a50-65d7-4f09-b41d-a12d0e8e2c32](https://github.com/user-attachments/assets/1eeb620b-14f1-4169-9449-5d0b65b4b34e)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
