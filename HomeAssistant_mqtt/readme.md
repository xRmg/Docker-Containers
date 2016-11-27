# Docker compose for Home Assistant and MQTT.

This is my docker-compose file for running the latest version of Home Assistant and MQTT

Upgrading is done by stopping the containers, removing the container, pulling the latest version and starting again.

## Upgrade procedure

* docker-compose stop
* docker-compose rm
* docker-compose pull
* docker-compose start

## Included the startup script.
