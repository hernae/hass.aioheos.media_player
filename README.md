# hass.aioheos.media_player

Denon Heos media player for Home Assistant.

## install

    > cp heos.py ~/.homeassistant/custom_components/media_player/

## configuration

    media_player:
        platform: heos
        host: <hostname>
        name: Name of the device
        username: <heos_username>
        password: <heos_password>

