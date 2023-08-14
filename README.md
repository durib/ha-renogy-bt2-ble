# Home Assistant Add-on: Renogy DCC50S/DCC30S BT-2

Monitor Renogy DCC50S and DCC30S over Bluetooth using the BT-2 module, sensor data is read from the charger and sent to Home Assistant through MQTT.


## Features

* Uses Bluetooth Low-Energy (BLE) for wireless communication
* Integrates with Home Assistant Energy dashboard
* Captures:
   * House Battery Voltage, Current, Power and Temperature
   * Alternator Voltage, Current and Power
   * Solar Voltage, Current and Power
   * Charger State, Current, Power and Temperature
   * Battery Fully Charged, Over-Discharged and Total Working Days Counts
   * Highest/Lowest Daily Current and Power
   * Total Daily/Lifetime Accumulated Power

## Install
[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fdurib%2Fha-renogy-bt2-ble)

* Install, configure and start Mosquito MQTT broker.
* Add repository to Home Assistant add-on Store `https://github.com/durib/ha-renogy-bt2-ble`
* Install and configure add-on Renogy DCC50S/DCC30S BT-2

## Credits
* [ard00d renogy-bt2-ha-ble](https://github.com/ard00d/renogy-bt2-ha-ble) - Home Assistant (MQTT) integration for the Renogy BT-2 Bluetooth module, written in Python.
* [neilsheps Arduino library](https://github.com/neilsheps/Renogy-BT2-Reader) - Reverse engineering of Renogy BT-2 protocol.

## License
[GPLv3](LICENSE)