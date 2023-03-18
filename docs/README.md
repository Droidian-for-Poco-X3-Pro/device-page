## Features & Usability

|                               	|    	|                                  	|    	|                      	|   	|
|-------------------------------	|----	|----------------------------------	|----	|----------------------	|---	|
| Manual brightnes              	|  ✅ 	| Battery lifetime > 24h from 100% 	|  ✅ 	| Automatic brightness  |  ✖️  	|
| No reboot needed for 1 week      	|  ✅	| Fingerprint reader  	                |  ✖️✖️   | Waydroid		|  ✅	|
| Torchlight                    	|  ✅	| Boot into UI                     	|  ✅ 	| GPS                 	| ✖️ ✖️  	|
| Vibration                     	|  ✅ 	| Hardware video playback          	|  ✅ 	| Proximity          	|  ✅ 	|
| Flashlight                    	|  ✅	| Anbox patches                    	|  ✅ 	| Rotation            	|  ✅ 	|
| Photo                         	|  ✅	| AppArmor patches                 	|  ✅ 	| Touchscreen          	|  ✅ 	|
| Video                         	|  ✅	| Battery percentage               	|  ✅ 	| Earphones           	|  ✅	|
| Switching between cameras     	|  ✅	| Offline charging                 	|  ✅	| Loudspeaker          	|  ✅	|
| Dual SIM functionality        	| ✖️ ✖️  	| Online charging                  	|  ✅ 	| Microphone          	|  ✅	|
| Carrier info, signal strength 	|  ✅ 	| SD card detection and access     	|  ✅ 	| Volume control       	|  ✅ 	|
| Data connection               	|  ✅ 	| RTC time                         	|  ✅ 	| Pin unlock           	|  ✅ 	|
| Incoming, outgoing calls      	|  ✅ 	| Shutdown / Reboot                	|  ✅ 	| ADB access          	|  ✖️✖️  	|
| MMS in, out                   	|  ❔ 	| Wireless External monitor        	|  ✖️✖️	| MTP access           	|  ✖️✖️  	|
| SMS in, out                    	|  ✅ 	| Bluetooth                        	|  ✅ 	| WiFi			|  ✅	|
| Change audio routings          	|  ✅	| Flight mode                      	|  ✅ 	| Hotspot		|  ✅	|
| Voice in calls                	|  ✅ 	|

- **✅** *Confirmed working.*
- **✅✖️** *Working to some extent but with issues.*
- **✖️** *Not Working.*
- **❔** *Not tested.*
- **✖️✖️** *Global issue.*

## Requirements
- Android 10 firmware for your device:
  - Redmi Note 7: https://xiaomifirmwareupdater.com/miui/lavender/stable/V11.0.6.0.PFGMIXM/

## Files
- Download the latest fastbootable image: [droidian-UNOFFICIAL-phosh-phone-xiaomi_lavender-api28-arm64-nightly_XXXXXXXX.zip](https://github.com/droidian-lavender/droidian-images/releases/tag/nightly).

## Installation
* Extract the archive
* run the `flash_all` script
* Boot to fastboot and let the script flash everything.

## UBports Installer
- Alternatively the UBports installer can also be used to install Droidian.

## Notes
- The default password is `1234`.

## Bugs
- Encryption is currently not supported.
- Mobile data needs an APN to be set up from Settings -> Mobile -> Acess Point Names.
- Mobile data might stop working after making or recieving phone calls. Toggle Mobile Data from the settins off/on.
- Dual SIM functionality is currently not implemented in Phosh so only one SIM works at the moment.

## Final notes
- I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.
- Please do some research if you have any concerns about features included in the products you find here before flashing it!
- YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.

# Support
- Droidian telegram group: [@DroidianLinux](https://t.me/DroidianLinux).
