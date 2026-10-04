# ESP32 WiFi Connect

## Aim

To connect the ESP32 to a WiFi network and display its assigned IP address through the Serial Monitor.

## Components Required

* ESP32 Development Board
* WiFi Network
* Wokwi ESP32 Simulator

## Software Requirements

* Arduino IDE or Wokwi Simulator

## Procedure

1. Create a new ESP32 project in Wokwi.
2. Include the WiFi library.
3. Configure the WiFi SSID and password.
4. Connect the ESP32 to the WiFi network using `WiFi.begin()`.
5. Check the connection status.
6. Display the assigned IP address using `WiFi.localIP()`.

## Expected Output

```text
Connecting to WiFi...
WiFi Connected Successfully!
IP Address: 10.10.0.2
```

*Note: The actual IP address may vary.*

## Result

The ESP32 connects to the WiFi network and displays its assigned IP address through the Serial Monitor.
