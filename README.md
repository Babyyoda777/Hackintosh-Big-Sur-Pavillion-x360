# Hackintosh-Big-Sur-Pavillion-x360
Files for my Hackintosh Laptop
Feel free to use this to cross check your own hackintosh, but by no means is this perfect.

## Specs:
* CPU: i3 1005G1
* GPU: Intel UHD (G1) - Acceleration working
* Keyboard: PS/2
* Trackpad: ELAN 0722
* Camera: HP Wide Vision
* USB Ports: 2x USB A 3.0, 1x USB C
* Touchscreen: yes
* Bluetooth and WiFi: Both Intel (no airdrop)
* Audio: Realtek ALC287

## What does work:
  * Wifi
  * Graphics
  * Keyboard
  * iServices
  * Trackpad 
  * Brightness keys
  * Bluetooth 
  * Camera

## Doesn't work (yet):
  * Audio
  * HDMI


<key>PciRoot(0x0)/Pci(0x1F,0x3)</key>
			<dict>
				<key>AAPL,slot-name</key>
				<string>Internal@0,31,3</string>
				<key>device_type</key>
				<string>Multimedia audio controller</string>
				<key>model</key>
				<string>Ice Lake-LP Smart Sound Technology Audio Controller</string>
			</dict>
