# My Home Assistant Setup

Welcome to my current Home Assistant setup! I am running my deployment of Home Assistant in a [Docker](https://www.docker.com/) container on a old desktop computer. I am also running the following Docker containers alongside Home Assistant:

- [Node-RED](https://nodered.org/)
- [Mosquitto](https://mosquitto.org/)
- [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt/wiki)

I am also running a Docker containers on a [Raspberry Pi 3](https://amzn.to/2wy4Fjc) and a few [Raspberry Pi Zero Ws](https://amzn.to/2oi9mtv) to boost a Bluetooh MiFlora sensor over WiFi and to run presence detection.

- [MiFlora MQTT Daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon)

### Hardware

Here is a running list of the hardware I have used to build my smart apartment:

**Sensors**

- [ESP-01 Module with CH340 USB Adapter](https://amzn.to/2ubea7l) (x 1)
- [Xiaomi Aqara Human Body Sensor](https://www.aliexpress.com/wholesale?catId=0&initiative_id=&SearchText=xiaomi+aqara+human+body+sensor) (x 3)
- [Xiaomi MiFlora Flower Care Smart Monitor](https://amzn.to/2MlGpr4) (x 4)
- [Xiaomi Mi Door and Window Sensor](https://www.aliexpress.com/wholesale?catId=0&initiative_id=&SearchText=xiaomi+mi+door+window+sensor)
- [Xiaomi Mi Magic Cube](https://www.aliexpress.com/wholesale?catId=0&initiative_id=&SearchText=xiaomi+mi+aqara+cube)

**Switches**

- [Sonoff Wifi Basic Switch](https://amzn.to/2vjfGVq) flashed with [ESPHome](https://esphome.io/) (x 15)

