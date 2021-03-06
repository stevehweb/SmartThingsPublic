# Smartsense Motion Sensor



Works with: 

* [Samsung SmartThings Motion Sensor](https://shop.smartthings.com/#!/products/samsung-smartthings-motion-sensor)

## Table of contents

* [Capabilities](#capabilities)
* [Health](#device-health)
* [Battery](#battery-specification)

## Capabilities

* **Configuration** - _configure()_ command called when device is installed or device preferences updated
* **Motion Sensor** - can detect motion
* **Battery** - defines device uses a battery
* **Refresh** - _refresh()_ command for status updates
* **Health Check** - indicates ability to get device health notifications

## Device Health

A Category C2 motion sensor with maxReportTime of 1 hr.
Check-in interval is double the value of maxReportTime for Zigbee device. 
This gives the device twice the amount of time to respond before it is marked as offline.
Check-in interval = 2*60 = 120 min

## Battery Specification

One CR123A 3V battery is required.