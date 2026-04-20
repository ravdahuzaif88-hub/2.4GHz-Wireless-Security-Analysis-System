# 2.4GHz Wireless Security Analysis System

ESP32-based wireless security toolkit integrating three NRF24L01 radio modules 
for real-time 2.4GHz spectrum analysis, BLE spoofing, and Wi-Fi deauthentication testing.

## Hardware Used
- ESP32-WROOM-32U Dev Board
- 3x NRF24L01 with adapter boards (YL-105)
- 0.96 inch SSD1306 OLED Display
- 4x Tactile Push Buttons

## Features
- 2.4GHz spectrum scanner across 128 channels
- Wi-Fi and BLE jammer
- BLE device spoofer (Apple, Samsung, Google)
- Sour Apple attack
- Wi-Fi deauthentication
- Real-time OLED spectrum display

## Circuit Connections
- NRF24 #1 — CE: GPIO5, CSN: GPIO17
- NRF24 #2 — CE: GPIO16, CSN: GPIO4
- NRF24 #3 — CE: GPIO15, CSN: GPIO2
- Shared SPI — SCK: GPIO18, MOSI: GPIO23, MISO: GPIO19
- OLED — SDA: GPIO21, SCL: GPIO22

## Built With
- Arduino IDE
- ESP32 Arduino Core v3.3.8
- RF24 Library
- U8g2 Library

## Note
This project is for educational and authorised research purposes only.
