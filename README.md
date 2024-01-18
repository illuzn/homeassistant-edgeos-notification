# Home Assistant EdgeOS Unknown Device Notification

This Home Assistant blueprint generates a notification (notify.notify or notify.persistent_notification) upon an unknown device connecting to your network. It
can also be used to notify upon any connection/ disconnection from your network
that is acquired by DHCP lease (leave the filters blank).

Prerequisites:
* Home Assistant 2024.1.0 (Earlier versions are untested)
* [EdgeOS Home Assistant Custom Component](https://github.com/elad-bar/ha-edgeos) - Observer only access is sufficient

## Blueprint

Import `edgeos_unknown_device_blueprint.yaml` yourself manually or:

[![Import blueprint to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Filluzn%2Fhomeassistant-edgeos-notification%2Fblob%2Fmain%2Fedgeos_unknown_device_blueprint.yaml)