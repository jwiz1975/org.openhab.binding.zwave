---
layout: documentation
title: DTHERMZ6 - ZWave
---

{% include base.html %}

# DTHERMZ6 Living Connect Z Thermostat
This describes the Z-Wave device *DTHERMZ6*, manufactured by *Danfoss* with the thing type UID of ```danfoss_dthermz6_00_000```.

![DTHERMZ6 product image](https://www.cd-jackson.com/zwave_device_uploads/502/502_default.jpg)


The DTHERMZ6 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The DTHERMZ6 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

### Wakeup Information

The DTHERMZ6 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.

## Channels

The following table summarises the channels available for the DTHERMZ6 -:

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|
| Sensor (temperature) | sensor_temperature | Temperature | Number:Temperature | 
| Setpoint (heating) | thermostat_setpoint | Temperature | Number:Temperature | 
| Battery Level | battery-level | Battery | Number |
| Clock Time Offset | time_offset | Temperature | Number | 

### Sensor (temperature)

Indicates the current temperature.

The ```sensor_temperature``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Setpoint (heating)

Sets the thermostat setpoint.

The ```thermostat_setpoint``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Battery Level

Represents the battery level as a percentage (0-100%). Bindings for things supporting battery level in a different format (e.g. 4 levels) should convert to a percentage to provide a consistent battery level reading.

The ```battery-level``` channel supports the ```Number``` item and is in the ```Battery``` category.

### Clock Time Offset

Provides the current time difference for the devices time.

The ```time_offset``` channel supports the ```Number``` item and is in the ```Temperature``` category.



## Device Configuration

The device has no configuration parameters configured.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The DTHERMZ6 supports 1 association group.

### Group 1: Target for Wakeup and Override Notifications

This group supports 1 node.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V6| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_CLIMATE_CONTROL_SCHEDULE_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_PROTECTION_V2| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_CLOCK_V1| |
| COMMAND_CLASS_WAKE_UP_V2| |
| COMMAND_CLASS_VERSION_V1| |
| COMMAND_CLASS_MULTI_CMD_V1| |

### Documentation Links

* [Product Manual](https://www.cd-jackson.com/zwave_device_uploads/502/THERMZ6.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/502).
