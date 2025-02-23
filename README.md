# Smarty - Home Assistant config

**NOTE**: This is not my first [Home Assistant][home-assistant] configuration that you can find on Github. Take also a look at these [Home Assistant configuration repositories][smarthomes].

---

You will probably think, what is Home Assistant!? Well Home Assistant is a open source home automation platform that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts. Perfect to run on a Raspberry Pi or a local server.

Use the code from this repo for your own Home Assistant environment, keep in mind to not always copy everything line-by-line. If you have any questions, feel free to ask them via email or socials!

## Status Information

| [![Home Assistant CI][homeassistantci-shield]][homeassistantci] | [![GitHub Last Commit][last-commit-shield]][commits]|
|:---:|:---:|
| Shows whether the configuration in this repo is valid | Shows how up to date this repo is |
| ![Project Maintenance][maintenance-shield] | [![GitHub Activity][commits-shield]][commits] |
| Is this repository still actively maintained? | Shows how active I am with this repo annually |
| [![GitHub Stars][stars-shield]][stars] | [![Buy Me A Fanta][paypal-shield]][paypal] |
| Please :star: this repo if you find it useful, like these people have | If this config was helpful, you could buy a fanta :tropical_drink: for me :smile: |

## Current House Configuration

Some time ago we moved to another part of the country, which also meant the end of the old Home Assistant configuration and a fresh start in the new house. For example, a network infrastructure upgrade with Ubiquiti Unifi hardware for the internet at home and a server cabinet where everything comes together, super cool!

**My Home Assistant Server**

Below my server setup on which I run Home Assistant:

- [Intel Baby Canyon NUC7i5BNH][intel-nuc] - Inside it 16GB RAM and 500GB SSD.
- Running a [Proxmox][proxmox] server, with a [Home Assistant OS][ha-os] VM on it.
- [Aeotec USB Z-Stick][zwave-stick] - Z-Wave Plus
- [Deconz - Conbee II][conbee] stick

**And I use the following hardware in my house:**

- Xiaomi Aqara [Temperature & Humidity Sensors][xiaomi_temp-shop] (Zigbee)
- Xiaomi Aqara [Window Door Sensors][xiaomi_door-shop] (Zigbee)
- [Blitzwolf BW-SHP13][bw_shp13-shop] smart plugs (Zigbee)
- [Blitzwolf BW-SHP2][bw_shp2-shop] smart plugs (ESPHome flashed)
- [Fibaro Wall Plug][fibaro_wall-shop] (Z-Wave)
- [Fibaro Smoke Sensor][fibaro_smoke-shop] (Z-Wave)
- Shelly 1 (ESPHome flashed)
- [Shelly Dimmer 2][shelly_dimmer_2] (Wi-Fi)
- [Shelly 2PM][shelly_2pm] (Wi-Fi)

## Need help or questions? 🤔

If you have a specific question about my configuration send me a Private message (PM) on the HA forum, my username is **[klaasnicolaas](https://community.home-assistant.io/u/klaasnicolaas)**. Or send me a message via Discord, my username is **Mister Nicolaz**. If you have found any bug or errors, please submit an issue here on Github and I will get it fixed.

## Links

- [Home Assistant Homepage](https://home-assistant.io/)
- [Home Assistant Forums](https://community.home-assistant.io/)
- [Home Assistant Discord Chat](https://discord.gg/c5DvZ4e)
- [Other Featured Home Assistant Configurations](https://home-assistant.io/cookbook/)
- [Home Assistant GitHub Source Repository](https://github.com/home-assistant/home-assistant)
- [Official Home Assistant Demo](https://home-assistant.io/demo/)

## License

MIT License

Copyright (c) 2022-2025 Klaas Schoute

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<!-- Shields -->
[homeassistantci-shield]: https://github.com/klaasnicolaas/smarty-homeassistant-config/actions/workflows/home_assistant.yaml/badge.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/klaasnicolaas/smarty-homeassistant-config.svg?color=blue&style=plasticr
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/klaasnicolaas/smarty-homeassistant-config.svg
[stars-shield]: https://img.shields.io/github/stars/klaasnicolaas/smarty-homeassistant-config.svg
[paypal-shield]: https://img.shields.io/badge/BuyMeAFanta-Paypal-orange.svg

<!-- Repository link -->
[homeassistantci]: https://github.com/klaasnicolaas/smarty-homeassistant-config/actions/workflows/home_assistant.yaml
[commits]: https://github.com/klaasnicolaas/smarty-homeassistant-config/commits/master
[stars]: https://github.com/klaasnicolaas/smarty-homeassistant-config/stargazers
[home-assistant]: https://home-assistant.io
[paypal]: https://www.paypal.me/dexterfpv

[smarthomes]: https://github.com/klaasnicolaas?tab=repositories&q=home-assistant-config
[proxmox]: https://www.proxmox.com/en/
[ha-os]: https://github.com/whiskerz007/proxmox_hassos_install

<!-- Products -->
[intel-nuc]: https://www.intel.com/content/www/us/en/products/boards-kits/nuc/kits/nuc7i5bnh.html
[conbee]: https://www.phoscon.de/en/conbee2
[zwave-stick]: https://aeotec.com/z-wave-usb-stick
[xiaomi_temp-shop]: https://www.banggood.com/bang/?tt=16956_12_417111_&r=%2FAqara-Smart-Home-Zigbee-Temperature-and-Humidity-Sensor-Thermometer-Hygrometer-Digital-Sensor-From-Eco-System-p-1148666.html
[xiaomi_door-shop]: https://www.banggood.com/bang/?tt=16956_12_417111_&r=%2FAqara-Zigbee-1_2-Version-Window-Door-Sensor-Smart-Home-Kit-Remote-Alarm-Eco-System-p-1149705.html
[bw_shp13-shop]: https://www.banggood.com/bang/?tt=16956_12_417111_&r=%2FBlitzWolf-BW-SHP13-ZgBee-3_0-Smart-WIFI-Socket-16A-EU-Plug-Electricity-Metering-APP-Remote-Controller-Timer-Work-with-Amazon-Alexa-Google-Home-p-1679992.html
[bw_shp2-shop]: https://www.banggood.com/bang/?tt=16956_12_417111_&r=%2FBlitzWolf-BW-SHP2-16A-Smart-WIFI-Socket-220V-EU-Plug-Work-with-Amazon-Alexa-Google-Assistant-Compatible-with-BlitzWolf-Tuya-APP-p-1292899.html
[fibaro_wall-shop]: https://partner.bol.com/click/click?p=2&t=url&s=1208424&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Ffibaro-wall-plug-type-f-slimme-stekker-incl-energiemeter-werkt-met-toon-fibaro-home-center-en-homey%2F9200000072900555%2F&name=FIBARO%20Wall%20Plug%20-%20Type%20F%20(NL)
[fibaro_smoke-shop]: https://partner.bol.com/click/click?p=2&t=url&s=1208424&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Ffibaro-smoke-sensor-draadloze-rookmelder-werkt-met-fibaro-toon-en-homey-z-wave-plus%2F9200000045628365%2F&name=FIBARO%20Smoke%20Sensor%20-%20Draadloze%20rookmelder
[shelly_dimmer_2]: https://www.shelly.com/en/products/shop/shelly-dimmer2
[shelly_2pm]: https://www.shelly.com/en/products/shop/shelly-plus-2-pm