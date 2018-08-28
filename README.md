# My Home Assistant Setup

Welcome to my current Home Assistant setup! I am running my deployment of Home Assistant in a [Docker](https://www.docker.com/) container on a [Raspberry Pi 3](https://amzn.to/2wy4Fjc). I am also running the following Docker containers alongside Home Assistant:

- [Node-RED](https://nodered.org/)
- [Mosquitto](https://mosquitto.org/)
- [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt/wiki)

I am also running a Docker container on a [Raspberry Pi Zero W](https://amzn.to/2oi9mtv) in my bedroom to boost a Bluetooh MiFlora sensor over WiFi.

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

- [Sonoff Wifi Basic Switch](https://amzn.to/2vjfGVq) flashed with [ESPEasy](https://www.letscontrolit.com/wiki/index.php/ESPEasy) (x 8)
- [Wemo Mini Smart Plug](https://amzn.to/2Od2LeG) (x 3)
