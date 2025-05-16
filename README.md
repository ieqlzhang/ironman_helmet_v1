# Ironman Helmet Project

An ESP32-based Ironman helmet controller with LED animations and sensor integration.

## Hardware
- ESP32-C3 microcontroller
- WS2812B LED strips
- MPU6050 accelerometer/gyroscope
- Sound module (DFPlayer Mini)

## Installation
1. Install [PlatformIO](https://platformio.org/) extension in VSCode
2. Clone this repository
3. Connect hardware components as per wiring diagram

```bash
git clone https://github.com/ieqlzhang/ironman_helmet_v1.git
cd ironman_helmet_v1
pio run
```

## Usage
Upload the firmware to ESP32:
```bash
pio run -t upload
```

Control modes:
- Button press cycles through animation patterns
- Head tilt controls direction using MPU6050
- Voice commands via Bluetooth (WIP)

## License
MIT License - See LICENSE for details
