# esp8266_gps_tracker_home_assistant
ESP8266 GPRS Tracker Home Assistant Owntracks

Using the TinyGPS+ lib to parse GPS position data into NMEA and then post that data according to the owntracks format to Home Assistant via MQTT.

In Home Assistant a device_tracker.xxx entity will automatically be created and the unit will be tracked

This is VERY much Beta stage, it has been tested with Home Assistant version 0.92.2

The codebase used is from: https://jpmens.net/2016/04/16/a-tiny-esp8266-based-gps-tracker/
His github is: https://github.com/jpmens/pico thanks @jpmens! <3
