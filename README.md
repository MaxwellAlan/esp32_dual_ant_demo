# ESP32 Dual Antenna Demo

## Env Setup
- IDF Version: release/v4.4 & master
- Board: ESP32-WROOM-DA

## Usage

### Build & Flash
- idf.py flash monitor -p /dev/ttyUSB?

### Support Commands

- ant -d [tx|rx] -p [pin num] -i [0|1|2] -o [0~15]
- scan [ssid]
- sta ssid [password]
- ap ssid [password]
- query
