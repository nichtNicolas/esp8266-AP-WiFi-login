# esp8266-AP-WiFi-login

Allows you to save credentials of an WiFi Access Point in the EEPROM and connect to it after rebooting

#### Features:
- [x] WebUI
- [ ] Settings
- [x] EEPROM saving
- [ ] control of GPIO pins in the WebUI
- [ ] custom server events

#### Usage:

__Step 1:__ first of all you need to import the esp8266 to your Arduino IDE
__Step 2:___ open sketch.ino and flash it on your device
__Step 3:___ connect to the Access Point created by the esp8266
__Step 4:___ open your Browser and visit *192.168.4.1*
__Step 5:___ type in your ssid and password
__Step 6:___ restart the esp8266
