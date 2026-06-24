# Wearable Bone Conduction Hearing Aid / Headphone PCB  

Wearable bone-conduction hearing aid headphone PCB based on the ESP32-S3, integrating an I2S MEMS microphone input, I2S audio amplifier output, LiPo battery charging, USB-C power/programming support, and a bone-conduction transducer interface. This project focused on end-to-end wearable audio hardware development, including BOM creation, schematic design, PCB layout, and board assembly through JLCPCB. 

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

<img src="images/Bone%20Conduction%20Power%20Schematic.png" alt="Bone conduction power schematic" width="800">

### Processor

<img src="images/Bone%20Conduction%20Processor%20Schematic.png" alt="Bone conduction processor schematic" width="800">

### Audio

<img src="images/Bone%20Conduction%20Audio%20Schematic.png" alt="Bone conduction audio schematic" width="800">

## Layout

The 2-layer PCB layout was designed to fit the audio input/output, power, charging, and programming circuitry into a compact wearable form factor.

<img src="images/Bone%20Conduction%20Layout.png" alt="Bone conduction PCB layout" width="700">

## 3D View

<img src="images/Bone%20Conduction%203D%20Viewer.png" alt="Bone conduction PCB 3D view" width="600">

## Assembled Board

<img src="images/Bone%20Conduction%20Board.png" alt="Received assembled bone conduction PCB" width="500">
