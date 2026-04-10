# iot-sensor-stm32
# STM32 IoT Monitor

## Description
Système de monitoring temps réel : STM32F4 + ESP8266 → ThingSpeak

## Hardware
- STM32F407
- ESP8266 WiFi module
- Capteur analogique sur PA1 (ADC1 CH1)

## Architecture
STM32 → UART2 (DMA) → ESP8266 → WiFi → ThingSpeak
