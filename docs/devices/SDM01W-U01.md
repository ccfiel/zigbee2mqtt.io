---
title: "BITUO TECHNIK SDM01W-U01 control via MQTT"
description: "Integrate your BITUO TECHNIK SDM01W-U01 via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2025-06-01T17:54:42
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# BITUO TECHNIK SDM01W-U01

|     |     |
|-----|-----|
| Model | SDM01W-U01  |
| Vendor  | [BITUO TECHNIK](/supported-devices/#v=BITUO%20TECHNIK)  |
| Description | Smart energy monitor for 3P+N system |
| Exposes | power_reactive, power_reactive_phase_b, power_reactive_phase_c, power_apparent, power_apparent_phase_b, power_apparent_phase_c, power_factor_phase_b, power_factor_phase_c, total_power, total_power_reactive, total_power_apparent, identify, switch (state), power, voltage, ac_frequency, power_factor, current, energy, produced_energy, power_phase_b, power_phase_c, voltage_phase_b, voltage_phase_c, current_phase_b, current_phase_c, current_neutral |
| Picture | ![BITUO TECHNIK SDM01W-U01](https://www.zigbee2mqtt.io/images/devices/SDM01W-U01.png) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->


<!-- Notes END: Do not edit below this line -->



## Options
*[How to use device type specific configuration](../guide/configuration/devices-groups.md#specific-device-options)*

* `power_calibration`: Calibrates the power value (percentual offset), takes into effect on next report of device. The value must be a number.

* `power_precision`: Number of digits after decimal point for power, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `voltage_calibration`: Calibrates the voltage value (percentual offset), takes into effect on next report of device. The value must be a number.

* `voltage_precision`: Number of digits after decimal point for voltage, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `ac_frequency_calibration`: Calibrates the ac_frequency value (absolute offset), takes into effect on next report of device. The value must be a number.

* `ac_frequency_precision`: Number of digits after decimal point for ac_frequency, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `current_calibration`: Calibrates the current value (percentual offset), takes into effect on next report of device. The value must be a number.

* `current_precision`: Number of digits after decimal point for current, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `energy_calibration`: Calibrates the energy value (percentual offset), takes into effect on next report of device. The value must be a number.

* `energy_precision`: Number of digits after decimal point for energy, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `power_phase_b_calibration`: Calibrates the power_phase_b value (percentual offset), takes into effect on next report of device. The value must be a number.

* `power_phase_b_precision`: Number of digits after decimal point for power_phase_b, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `power_phase_c_calibration`: Calibrates the power_phase_c value (percentual offset), takes into effect on next report of device. The value must be a number.

* `power_phase_c_precision`: Number of digits after decimal point for power_phase_c, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `voltage_phase_b_calibration`: Calibrates the voltage_phase_b value (percentual offset), takes into effect on next report of device. The value must be a number.

* `voltage_phase_b_precision`: Number of digits after decimal point for voltage_phase_b, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `voltage_phase_c_calibration`: Calibrates the voltage_phase_c value (percentual offset), takes into effect on next report of device. The value must be a number.

* `voltage_phase_c_precision`: Number of digits after decimal point for voltage_phase_c, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `current_phase_b_calibration`: Calibrates the current_phase_b value (percentual offset), takes into effect on next report of device. The value must be a number.

* `current_phase_b_precision`: Number of digits after decimal point for current_phase_b, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `current_phase_c_calibration`: Calibrates the current_phase_c value (percentual offset), takes into effect on next report of device. The value must be a number.

* `current_phase_c_precision`: Number of digits after decimal point for current_phase_c, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `current_neutral_calibration`: Calibrates the current_neutral value (percentual offset), takes into effect on next report of device. The value must be a number.

* `current_neutral_precision`: Number of digits after decimal point for current_neutral, takes into effect on next report of device. This option can only decrease the precision, not increase it. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `identify_timeout`: Sets the duration of the identification procedure in seconds (i.e., how long the device would flash).The value ranges from 1 to 30 seconds (default: 3). The value must be a number with a minimum value of `1` and with a with a maximum value of `30`

* `state_action`: State actions will also be published as 'action' when true (default false). The value must be `true` or `false`


## Exposes

### Power reactive (numeric)
Instantaneous measured reactive power.
Value can be found in the published state on the `power_reactive` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VAR`.

### Power reactive phase b (numeric)
Instantaneous measured reactive power on phase B.
Value can be found in the published state on the `power_reactive_phase_b` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VAR`.

### Power reactive phase c (numeric)
Instantaneous measured reactive power on phase C.
Value can be found in the published state on the `power_reactive_phase_c` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VAR`.

### Power apparent (numeric)
Instantaneous measured apparent power.
Value can be found in the published state on the `power_apparent` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VA`.

### Power apparent phase b (numeric)
Instantaneous measured apparent power on phase B.
Value can be found in the published state on the `power_apparent_phase_b` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VA`.

### Power apparent phase c (numeric)
Instantaneous measured apparent power on phase C.
Value can be found in the published state on the `power_apparent_phase_c` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VA`.

### Power factor phase b (numeric)
Instantaneous measured power factor on phase B.
Value can be found in the published state on the `power_factor_phase_b` property.
It's not possible to read (`/get`) or write (`/set`) this value.

### Power factor phase c (numeric)
Instantaneous measured power factor on phase C.
Value can be found in the published state on the `power_factor_phase_c` property.
It's not possible to read (`/get`) or write (`/set`) this value.

### Total power (numeric)
Total Active Power.
Value can be found in the published state on the `total_power` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `W`.

### Total power reactive (numeric)
Total Reactive Power.
Value can be found in the published state on the `total_power_reactive` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VAR`.

### Total power apparent (numeric)
Total Apparent Power.
Value can be found in the published state on the `total_power_apparent` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `VA`.

### Identify (enum)
Initiate device identification.
Value will **not** be published in the state.
It's not possible to read (`/get`) this value.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"identify": NEW_VALUE}`.
The possible values are: `identify`.

### Switch 
The current state of this switch is in the published state under the `state` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state": "ON"}`, `{"state": "OFF"}` or `{"state": "TOGGLE"}`.
To read the current state of this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"state": ""}`.

#### On with timed off
When setting the state to ON, it might be possible to specify an automatic shutoff after a certain amount of time. To do this add an additional property `on_time` to the payload which is the time in seconds the state should remain on.
Additionally an `off_wait_time` property can be added to the payload to specify the cooldown time in seconds when the switch will not answer to other on with timed off commands.
Support depends on the switch firmware. Some devices might require both `on_time` and `off_wait_time` to work
Examples : `{"state" : "ON", "on_time": 300}`, `{"state" : "ON", "on_time": 300, "off_wait_time": 120}`.

### Power (numeric)
Instantaneous measured power.
Value can be found in the published state on the `power` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"power": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `W`.

### Voltage (numeric)
Measured electrical potential value.
Value can be found in the published state on the `voltage` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"voltage": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `V`.

### AC frequency (numeric)
Measured electrical AC frequency.
Value can be found in the published state on the `ac_frequency` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"ac_frequency": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `Hz`.

### Power factor (numeric)
Instantaneous measured power factor.
Value can be found in the published state on the `power_factor` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"power_factor": ""}`.
It's not possible to write (`/set`) this value.

### Current (numeric)
Instantaneous measured electrical current.
Value can be found in the published state on the `current` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"current": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `A`.

### Energy (numeric)
Sum of consumed energy.
Value can be found in the published state on the `energy` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"energy": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `kWh`.

### Produced energy (numeric)
Sum of produced energy.
Value can be found in the published state on the `produced_energy` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"produced_energy": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `kWh`.

### Power phase b (numeric)
Instantaneous measured power on phase B.
Value can be found in the published state on the `power_phase_b` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"power_phase_b": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `W`.

### Power phase c (numeric)
Instantaneous measured power on phase C.
Value can be found in the published state on the `power_phase_c` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"power_phase_c": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `W`.

### Voltage phase B (numeric)
Measured electrical potential value on phase B.
Value can be found in the published state on the `voltage_phase_b` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"voltage_phase_b": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `V`.

### Voltage phase C (numeric)
Measured electrical potential value on phase C.
Value can be found in the published state on the `voltage_phase_c` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"voltage_phase_c": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `V`.

### Current phase B (numeric)
Instantaneous measured electrical current on phase B.
Value can be found in the published state on the `current_phase_b` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"current_phase_b": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `A`.

### Current phase C (numeric)
Instantaneous measured electrical current on phase C.
Value can be found in the published state on the `current_phase_c` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"current_phase_c": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `A`.

### Current neutral (numeric)
Instantaneous measured electrical current on neutral.
Value can be found in the published state on the `current_neutral` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"current_neutral": ""}`.
It's not possible to write (`/set`) this value.
The unit of this value is `A`.

