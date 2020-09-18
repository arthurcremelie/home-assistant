# My Home Assistant Configuration
You can do a lot of automation with Home Assistant: check out http://home-assistant.io.  

## Infrastructure
I run Home Assistant (formerly Hass.io) in a VM in Proxmox on an old HP laptop and it works great.

## Integrations

### SolarEdge
View solar panels statistics with the SolarEdge API integration.

### Somfy
Control and automate the roller shutters at home via Home Assistant.

### MQTT
Locally control WiFi bulbs and sockets. My bulbs and sockets come from Action (BE/NL) and come with Tuya installed out of the box, but I flashed them with Tasmota.

### Kodi
```
Service: kodi.call_method  
Entity: media_player.kodi
```

#### Start VRT NU addon
```
addonid: plugin.video.vrt.nu  
entity_id: media_player.kodi  
method: Addons.ExecuteAddon  
params:  
  command: activate  
```
  
#### Start YouTube addon
```
addonid: plugin.video.vrt.nu  
entity_id: media_player.kodi  
method: Addons.ExecuteAddon  
params:  
  command: activate  
```
