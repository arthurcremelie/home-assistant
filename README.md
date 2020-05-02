# My Home Assistant Configuration
You can do an incredible amount of things with Home Assistant: chekc out home-assistant.io.  

## Infrastructure
I run Home Assistant (formerly Hass.io) in a VM in Proxmox on an old HP laptop. It works really good.

## Integrations
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
