# home-assistant
My Home Assistant Configuration, love to automate things.


## Kodi integration
Service: kodi.call_method
Entity: media_player.kodi

### Start VRT NU addon
addonid: plugin.video.vrt.nu
entity_id: media_player.kodi
method: Addons.ExecuteAddon
params:
  command: activate
  
### Start YouTube addon
addonid: plugin.video.vrt.nu
entity_id: media_player.kodi
method: Addons.ExecuteAddon
params:
  command: activate
