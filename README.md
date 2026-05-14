# Pulse Code Modulation (PCM) using ESP32

This project demonstrates the basic working principle of Pulse Code Modulation (PCM) using an ESP32, an LDR sensor, and LEDs.

The system reads analog light intensity values from the LDR through the ESP32’s ADC (Analog-to-Digital Converter), performs quantization, and converts the signal into 4-bit binary PCM data. The encoded binary output is displayed using LEDs and monitored through the Serial Monitor.

## Features

* Analog signal acquisition using LDR
* ADC conversion using ESP32
* 4-bit quantization and binary encoding
* Real-time LED binary display
* Serial monitoring of sensor and PCM values

## Components Used

* ESP32 Development Board
* LDR (Light Dependent Resistor)
* 10kΩ Resistor
* 4 LEDs
* 220Ω Resistors
* Breadboard and Jumper Wires

## Working Principle

1. The LDR senses light intensity.
2. ESP32 samples the analog voltage using ADC.
3. The analog value is quantized into 16 discrete levels (4-bit).
4. The quantized value is encoded into binary form.
5. LEDs display the binary PCM output.

## Concepts Covered

* Pulse Code Modulation (PCM)
* Sampling
* Quantization
* Binary Encoding
* Analog-to-Digital Conversion (ADC)
* Digital Signal Representation

## Applications

* Digital Communication Systems
* IoT Sensor Data Processing
* Digital Telephony
* Embedded Signal Processing
* Data Acquisition Systems

## Future Improvements

* Wireless transmission using WiFi/Bluetooth
* Higher-bit PCM implementation
* Audio signal PCM encoding
* OLED display integration
* Cloud-based IoT monitoring

## Output

Changing the light intensity on the LDR changes the PCM binary output displayed on the LEDs and Serial Monitor in real time.

