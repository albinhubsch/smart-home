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

| Status | Sensor               | Product         | Amount | Brand       | Link |
| ------ | -------------------- | --------------- | ------ | ----------- | ---- |
| ✅     | Motion               |                 | 3      | Philips Hue |      |
| 🛒     | Magnetic Sensors     |                 | -      | Sonoff      |      |
| 🛒     | Prescence Sensors    |                 | -      | ?           |      |
| 🛒     | Water Leakage        |                 | -      | ?           |      |
| 🛒     | Temperature/Humidity |                 | -      | ?           |      |
| 🛒     | Smoke/Fire           |                 | -      | ?           |      |
| 🛒     | Plug Switches        | Ikea Inspelning | -      | Ikea        |      |

## Software

### Home Assistant

#### Zigbee2MQTT

The system uses Zigbee2MQTT within Home assistant...

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
