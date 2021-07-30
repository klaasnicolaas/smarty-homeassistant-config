## Smarty - Home Assistant config

This is the new repository to replace the old [Home Assistant config][old-repository] repository!

You will probably think, what is Home Assistant!? Well Home Assistant is a open source home automation platform that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts. Perfect to run on a Raspberry Pi or a local server.

To inspire others I have set up this github and update it regularly with new code. Be free to use code from this repo for your own Home Assistant environment, keep in mind that you can not always copy everything line by line. If you can not get out, you can always contact me.

## Current Configuration

Some time ago we moved to another part of the country, which also meant the end of the old Home Assistant configuration and a fresh start in the new house. For example, a network infrastructure upgrade with Ubiquiti Unifi hardware for the internet at home and a server cabinet where everything comes together, super cool!

## My HA Server

Below my server setup on which I run Home Assistant:

- [Intel Baby Canyon NUC7i5BNH][intel-nuc] - Inside it 16GB RAM and 500GB SSD.
- Running a [Proxmox][proxmox] server, with a [Home Assistant OS][ha-os] VM on it.
- [Aeotec USB Z-Stick](<https://aeotec.com/z-wave-usb-stick>) - Z-Wave Plus
- [Deconz - Conbee 2](<https://phoscon.de/en/conbee2>)

**And I use the following hardware in my house:**

- Xiaomi Aqara [Temperature & Humidity Sensors][xiaomi_temp]
- Xiaomi Aqara [Window Door Sensors][xiaomi_door]
- Blitzwolf [BW-SHP13][bw-shp13] smart plugs
- There is more soon :)

[old-repository]: https://github.com/klaasnicolaas/Smarthome-homeassistant-config
[proxmox]: https://www.proxmox.com/en/
[ha-os]: https://github.com/whiskerz007/proxmox_hassos_install

[xiaomi_temp]: https://www.banggood.com/Original-Xiaomi-Aqara-Atmos-Version-Temperature-Humidity-Sensor-Smart-Home-Thermometer-Hygrometer-p-1148666.html
[xiaomi_door]: https://www.banggood.com/Original-Xiaomi-Aqara-Zig_Bee-Version-Window-Door-Sensor-Smart-Home-Kit-Remote-Alarm-p-1149705.html
[bw-shp13]: https://www.banggood.com/BlitzWolf-BW-SHP13-Zigbee-3_0-Smart-WIFI-Socket-16A-EU-Plug-Electricity-Metering-APP-Remote-Controller-Timer-Work-with-Amazon-Alexa-Google-Home-p-1679992.html