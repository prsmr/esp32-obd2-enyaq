# esp32-obd2-enyaq

This is an OBD2 Reader with ESP32 for Skoda Enyaq EV. The raw data are converted to JSON and send to an MQTT broker.

I developed and tested this software with my Skoda Enyaq 2024 with ME 5.2.

## Hardware I used
- ESP32 Board
- DC/DC Converter 12V/5V

## Roadmap
- Initialize connection and read raw data
- Get Wifi Connection with onboard Hotspot
- Convert raw data to JSON
- Push JSON to MQTT
