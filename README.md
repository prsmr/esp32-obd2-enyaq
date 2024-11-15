# esp32-obd2-enyaq

An extended library for reading OBD-II data with ESP32 over CAN bus, especially for Skoda Enyaq. 
The raw data are converted to JSON and send to an MQTT broker via built-in WiFi Hotspot.

This is a fork of [esp32_obd2](https://github.com/MagnusThome/esp32_obd2).

I developed and tested this piece of software with my Skoda Enyaq 2024 with ME 5.2.

## Hardware I used
- ESP32 Board
- [Futheda OBD-II Adapter](https://amzn.eu/d/bqRweVg)
- DC/DC Converter 12V/5V

## Roadmap
- Initialize connection and read raw data
- Get Wifi Connection with onboard Hotspot
- Convert raw data to JSON
- Push JSON to MQTT
