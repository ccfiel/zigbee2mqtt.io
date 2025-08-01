---
title: "Tuya TS0601_air_quality_sensor control via MQTT"
description: "Integrate your Tuya TS0601_air_quality_sensor via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2021-10-30T12:58:50
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# Tuya TS0601_air_quality_sensor

|     |     |
|-----|-----|
| Model | TS0601_air_quality_sensor  |
| Vendor  | [Tuya](/supported-devices/#v=Tuya)  |
| Description | Air quality sensor |
| Exposes | temperature, humidity, co2, voc, formaldehyd |
| Picture | ![Tuya TS0601_air_quality_sensor](https://www.zigbee2mqtt.io/images/devices/TS0601_air_quality_sensor.png) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->
## Notes
* This device exposes a CO2 value, but [does not contain a CO2 sensor](https://community.home-assistant.io/t/blitzwolf-bw-ar01-air-quality-meter/338396). The CO2 value seems to be calculated from the VOC value and is completely wrong when compared to a real CO2 sensor.

* This device sends multiple value updates per second and poses a significant load for the Zigbee network.

<!-- Notes END: Do not edit below this line -->



## Options
*[How to use device type specific configuration](../guide/configuration/devices-groups.md#specific-device-options)*

* `temperature_calibration`: Calibrates the temperature value (absolute offset), takes into effect on next report of device. The value must be a number.

* `temperature_precision`: Number of digits after decimal point for temperature, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `humidity_calibration`: Calibrates the humidity value (absolute offset), takes into effect on next report of device. The value must be a number.

* `humidity_precision`: Number of digits after decimal point for humidity, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `co2_calibration`: Calibrates the co2 value (absolute offset), takes into effect on next report of device. The value must be a number.

* `voc_calibration`: Calibrates the voc value (absolute offset), takes into effect on next report of device. The value must be a number.

* `formaldehyd_calibration`: Calibrates the formaldehyd value (absolute offset), takes into effect on next report of device. The value must be a number.


## Exposes

### Temperature (numeric)
Measured temperature value.
Value can be found in the published state on the `temperature` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `°C`.

### Humidity (numeric)
Measured relative humidity.
Value can be found in the published state on the `humidity` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `%`.

### CO2 (numeric)
The measured CO2 (carbon dioxide) value.
Value can be found in the published state on the `co2` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `ppm`.

### VOC (numeric)
Measured VOC value.
Value can be found in the published state on the `voc` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `ppm`.

### Formaldehyd (numeric)
The measured formaldehyd value.
Value can be found in the published state on the `formaldehyd` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `mg/m³`.

