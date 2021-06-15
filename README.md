# hackintosh-Dell-M4800 by OpenCore 0.7.0
Hackintosh_M4800
Hackintosh for Dell Precision M4800

Intel Core i7 4900MQ
Intel HD Graphics 4600
NVIDIA Quadro K2100M
LCD LP156WF (eDP - 1920x1080)
Audio Realtek ALC292
O2 Micro SDCard Reader
BCM4352 802.11ac Wireless Network Adapter
Broadcom BCM20702A0 Bluetooth (integrated with BCM4352)
OpenCore - macOS Bigsur 11.2.3 tested

Functionality in OpenCore


what works: all hardware support

Power management
Sleep/idle
dual GPU
SDCard Reader
Dell Keyboard /Fn keys
USB2.0/3.0
Dell Dock
Audio
SMBus
LPC
X86 CPU
IMEI
Ethernet
WIFI
Bluetooth
HDMI Audio
Dual-boot with Windows/Linux
Facetime
Bootcamp
etc.
what not work:

None
Bugs:

sometimes touchpad broken when reboot - you can hit Win+Alt until login screen show up to solve this issue when boot up.
fix alc292 depends on https://github.com/badfellow/AppleALC_Dell_M4800/releases

