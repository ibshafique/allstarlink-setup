## Setting Up AllstarLink 

Version: ASL Version 2.0.0-beta.6

Hardware: Raspberry Pi 2 Model B V 1.1

Radio Interface: SHARI Pi3U

## Configurations

### /etc/asterisk/rpt.conf

rchannel = SimpleUSB/usb_53028

duplex = 0

eaanmode =2

### /etc/asterisk/echolink.conf

deny = *-L; *-R

### APRS Configuration

Make a file gps.conf. Create password for APRS-IS from: https://n5dux.com/ham/aprs-passcode/

gps.conf file should have permission for asterisk user and group.
