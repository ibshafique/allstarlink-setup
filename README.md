## Setting Up AllstarLink 

Version: ASL Version 3.4.5

Hardware: VM running on Debian 12 Bookworm

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


<img src="https://github.com/ibshafique/allstarlink-setup/blob/main/assets/aprs_map.png">



https://torun.com.bd/blog/Setting-Up-AllStarLink-ASL3-and-Associated-Tools
