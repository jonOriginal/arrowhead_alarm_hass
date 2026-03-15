# Arrowhead ECi alarm Homeassistant Integration

![arrowhead_alarms.png](https://raw.githubusercontent.com/jonOriginal/arrowhead_alarm_hass/refs/heads/main/docs/images/arrowhead_alarms.png)

Custom integration for Home Assistant to interface with Arrowhead ECi alarm systems

## Features

- Arm/Disarm individual partitions
- View alarm status
- Bypass Zones
- Control Outputs

## Requirements

- Arrowhead ECi panel
- EC-IoT module
- ECi Firmware version 10.3.50 or higher

## Installation

### One-click installation via HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=jonOriginal&repository=arrowhead_alarm&category=integration)

### Manual Installation

1. Use SSH to access your Home Assistant instance.

2. Clone this repository

```bash
git clone https://github.com/jonOriginal/arrowhead_alarm.git custom_components/arrowhead_alarm
```

3. Copy the `arrowhead_alarm` folder into your Home Assistant `custom_components` directory.

```bash
cp -r arrowhead_alarm/custom_components/arrowhead_alarm /config/custom_components/
```

4. Restart Home Assistant to load the new integration.