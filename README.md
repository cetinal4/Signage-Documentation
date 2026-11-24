# Signage-Documentation
<p>These were the steps I used to create a POC for the pi's, included is a step by step process of settings and commands and issues encountered on the way.</p>

<p>Used net install from pi imager (hold shift with ethernet plugged in during bootup) to install Ubuntu 26.04.X LTS, learned that pi does not have a UEFI bootloader which could be why I was having so much issues getting Ubuntu installed.</p>

<p>After installation I ran the following the following commands:</p>

1. Applied updates - "sudo apt update && sudo apt full-upgrade"
2. updated rpi eeprom - "sudo rpi-eeprom-update" "sudo rpi-eeprom-update -a"
3. reboot device "sudo reboot"
