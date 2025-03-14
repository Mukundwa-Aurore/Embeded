# MQTT Light Control

This project is a web-based application that controls a simulated IoT light using MQTT. It includes a web interface to send ON/OFF commands and a Python script to simulate an ESP8266 device.

## Files
- **index.html**: Web interface with buttons to turn the light ON/OFF and a visual bulb indicator.
- **light_simulation.py**: Python script that subscribes to MQTT messages and prints the light status.

## Setup
1. **Requirements**: 
   - Python 3.x
   - `paho-mqtt` library (`pip install paho-mqtt`)
2. **Run the simulation**: `python light_simulation.py`
3. **Open the web interface**: Open `index.html` in a browser.
4. **Test**: Click the buttons and observe the terminal output and bulb UI.

## Broker
- Uses `test.mosquitto.org` (WebSocket: 8081 for web, 1883 for Python).

## Features
- Simple UI with glowing bulb effect for ON state.
- Real-time MQTT communication.