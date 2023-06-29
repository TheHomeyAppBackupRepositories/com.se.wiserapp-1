# Schnieder Electric Wiser

Homey app for for use with Schnieder Electric devices without it's gateway.

### Changelog
v0.3.0
- Added zigbee driver ZB_NHMOTION_DIMMER_1: Motion Dimmer (WDE002374, WDE003374, WDE004374)
- Added zigbee driver ZB_NHMOTION_SWITCH_1: Motion Switch (WDE002367, WDE003367, WDE004367)
- Added zigbee driver ZB_SMARTPLUG_1: Smart Plug (CCT711119)
- Added zigbee driver ZB_SOCKET_OUTLET_1: 1-way socket (WDE002172)
- Added zigbee driver ZB_SOCKET_OUTLET_2: 2-way socket (WDE002182)
- Updated translations.
- Updated app images and icon.
- Verified zigbee driver ZB_NHPB_SWITCH_1: Push button switch (WDE00x348)
- Added setting Backlight Mode in driver ZB_NHPB_SWITCH_1 (how the small LED should indicate device on/off status).

v0.2.3
- Added support for Z-Wave ZW_MTN50x6xx devices.

v0.2.2
- New paired devices with dimming capability will remember brigthness between on/off by default.
- Updated homey-zigbeedriver@1.2.0, zigbee-clusters@1.2.1

v0.2.1
- Fix: Force device to update capability values when starting app.

v0.2.0
- Rewrite of all zigbee drivers to support SDK 3
- Added zigbee driver ZB_NHPB_SWITCH_1: Push button switch (WDE002476, WDE003476, WDE004476)

v0.1.0
- Added zigbee driver ZB_PUCK_SWITCH_1: Micro Module Switch (CCT5011-0001)
- Added support for min and max dimming
- Fixed the remember dim level, now the level is stored in the modules.

v0.0.1
- Initial version
- Added zigbee driver ZB_NHROTARY_DIMMER_1: Rotary Dimmer (WDE002334, WDE003334, WDE004334)
- Added zigbee driver ZB_1GANG_DIMMER_1: Push Dimmer (WDE002910)
- Added zigbee driver ZB_PUCK_DIMMER_1: Micro Module Dimmer (CCT5010-0001)
