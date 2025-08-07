# Smart Home

Very much in a state of planning and work in progress.

## Main Hardware Setup

| Type of Hardware      | Link                                                                                               |
| --------------------- | -------------------------------------------------------------------------------------------------- |
| Home Assistant Server | Raspberry Pi 5 8GB                                                                                 |
| Zigbee Coordinator    | [SMLIGHT slzb-06p7](https://smartlight.me/smart-home-devices/zigbee-devices/coordinator-slzb-06p7) |
| Camera                | Reolink Argus 3 Ultra                                                                              |
| Camera Hub            | Reolink Home HUB                                                                                   |
| 2 Yale Doorman        |                                                                                                    |

### Sensors/Switches/Relays

| Status | Sensor               | Product         | Amount | Brand       | Link                                                                                                |
| ------ | -------------------- | --------------- | ------ | ----------- | --------------------------------------------------------------------------------------------------- |
| ✅     | Motion               |                 | 3      | Philips Hue |                                                                                                     |
| 🛒     | Magnetic Sensors     |                 | -      | Sonoff      |                                                                                                     |
| 🛒     | Prescence Sensors    |                 | -      | ?           |                                                                                                     |
| 🛒     | Water Leakage        |                 | -      | ?           |                                                                                                     |
| 🛒     | Temperature/Humidity |                 | -      | ?           |                                                                                                     |
| 🛒     | Smoke/Fire           |                 | -      | ?           |                                                                                                     |
| ✅     | Smart Plug           | Ikea Inspelning | 4      | Ikea        | [Ikea Inspelning](https://www.ikea.com/se/sv/p/inspelning-stickpropp-smart-energimaetare-00569836/) |
| ✅     | Smart Plug           | Philips Hue     | 3      | Philips     | [Smart Plug](https://www.philips-hue.com/sv-se/p/hue-smart-plug/8719514342309)                      |

## Software

### Home Assistant

#### Zigbee2MQTT

The system uses Zigbee2MQTT within Home assistant...

#### Integrations

| Integration | Link |
| ----------- | ---- |
| Alarmo      |      |
| MQTT        |      |
| Proximity   |      |
| Reolink     |      |
| SMHI        |      |
| Roborock    |      |
| Sonos       |      |

#### HACS

Currently installed HACS

| HACS              | Link                                                 |
| ----------------- | ---------------------------------------------------- |
| Bubble Card       | https://github.com/Clooos/Bubble-Card                |
| button-card       | https://github.com/custom-cards/button-card          |
| Alarmo            | https://github.com/nielsfaber/alarmo                 |
| card-mod          | https://github.com/thomasloven/lovelace-card-mod     |
| Kiosk Mode        | https://github.com/NemesisRE/kiosk-mode              |
| Auto Backup       | https://github.com/jcwillox/hass-auto-backup         |
| Navbar Card       | https://github.com/joseluis9595/lovelace-navbar-card |
| Simple Swipe Card | https://github.com/nutteloost/simple-swipe-card      |
| Lucide Icons      | https://github.com/karlis-vagalis/hass-lucide-icons  |
