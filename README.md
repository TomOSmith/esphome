# esphome
My implementation of ESPHome devices and components

The following devices are supported:
* [a relative link](Sonoff T5.md|Sonoff T5 (TX Ultimate))
* Athom Smart Plug v2


Notes:
You will need your own secrets.yaml file.  It will need to define the following, hopefully obvious, items:
* wifi_ssid
* wifi_password
* domain
* gateway
* subnet
* dns
* ap_password
* api_encryption_key
* mqtt_broker
* mqtt_user
* mqtt_password
* timezone
* latitude
* longitude

These are all required in the packages/device.base.yaml configuration.  If you're playing with this I assume you can figure out what you might want to change.
