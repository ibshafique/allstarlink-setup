## Setting Up AllstarLink 

Version: ASL Version 2.0.0-beta.6

Hardware: Raspberry Pi 2 Model B V 1.1

Radio Interface: SHARI Pi3U

## Configurations

/etc/asterisk/rpt.conf
rchannel = SimpleUSB/usb_53028
duplex = 0
eaanmode =2

/etc/asterisk/echolink.conf
deny = *-L; *-R
