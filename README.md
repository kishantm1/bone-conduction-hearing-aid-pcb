# Wearable Bone Conduction Hearing Aid / Headphone PCB  

Wearable bone-conduction hearing aid headphone PCB based on the ESP32-S3, integrating an I2S MEMS microphone input, I2S audio amplifier output, LiPo battery charging, USB-C power/programming support, and a bone-conduction transducer interface. This project focused on end-to-end wearable audio hardware development, including BOM creation, schematic design, PCB layout, and board assembly through JLCPCB. Firmware is underway.

## Key Features

- Wearable headphone / hearing aid form factor
- ESP32-S3-based embedded audio platform
- I2S MEMS microphone input for audio capture
- I2S DAC/amplifier output for driving a bone-conduction transducer
- 3.7V battery-powered design

## Hardware Architecture

The board is centered around the ESP32-S3 microcontroller and integrates audio input, audio output, battery charging, power regulation, and programming/debug circuitry into a compact wearable PCB.

- **MCU:** ESP32-S3-WROOM-1
- **Microphone input:** I2S MEMS microphone for audio capture
- **Audio output:** I2S DAC/amplifier for driving the bone-conduction transducer
- **Transducer interface:** 2-pin connector for bone-conduction transducer output
- **Power:** 3.7V LiPo battery with USB-C charging and regulated 3.3V system power
- **Debug/programming:** Boot and reset support circuitry
- **Indicators:** Status LED for board/charging indication

## Schematic

### Power


### Processor


### Audio


## Layout

The 2-layer PCB layout was designed to fit the audio input/output, power, charging, and programming circuitry into a compact wearable form factor.

## 3D View


## Assembled Board
