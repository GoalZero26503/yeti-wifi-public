# Goal Zero Yeti with Wifi Wiki

## NOTICE 12/14/18
iOS 12.1.1 was released 12/5 which has updated Network Certificate settings that breaks the app. Yeti App 2.1.1 contains a fix and is in Apple App Store review. It will be released in the coming days.

## Release Notes

### Yeti App v2.1.1 (from v2.1)
##### iOS Release Date [PENDING]
##### Android Release Date (N/A)
* Fixes app compatibility issues with iOS 12.1.1

### Yeti WiFi Firmware 0.7.2 (from 0.4.26)
##### Release Date 12/13/2018
* Delete mobile pair after Factory reset
  * Previously paired devices lose ability to control Yeti after Factory Reset
* WiFi stores up to 5 WiFi networks
* WiFi search and reconnect to previous networks
* Faster response time from app changes
* Reports FW update progress percentage to app (requires fw >= 0.7.1)
* Battery Saving timeouts
  * Pair mode will timeout after 10 minutes of inactivity
  * Reconnect will timeout after 30 hours of unsuccessful reconnect
  * Direct mode will timeout after 30 hours of inactivity
* Fans turn on at 111°F instead of 95°F + any output enabled
  * Fans disabled when all outputs disabled
* Hold UNITS button to reset Watt Hour output
* Fixed WiFi enable after OTA update
* Hold LIGHTS + INFO to show Cycle Count
* Charging Blue LED indication changes
  * Blinks while charging (used to be solid ON)
  * Solid ON when done charging (used to turn OFF)

### Yeti App v2.1 (from v1.0)
##### iOS Release Date 12/3/2018
##### Android Release Date 12/3/2018
* Direct Connect - Take your Yeti off grid and continue to use the Yeti App
  * *Note: Direct Connect requires Yeti Firmware Update available in App Settings*
* Help button added - Get help from anywhere in the app
* Option to enter WiFi credentials manually
* Choose displayed temperature units (°F, °C)
* Choose International AC voltage units (120V, 230V)
* See your Yeti's WiFi signal strength
* Change multiple ports at once
* Receive firmware update notifications
* Notifications now include timestamp of when they occurred
* Notifications are more informative and less intrusive
* Correctly communicates yeti connectivity
* Pairing process syncing fixes
