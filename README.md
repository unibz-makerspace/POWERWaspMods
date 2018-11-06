# POWERWaspMods
Modified Firmware of the WASP models

## DWPOWERWASPF20_Rev5_NEO
This is a modded version of the original 2.0 firmware relased by WASPproject. This version can work only with Arduino 1.6.8.

See also:
 - [Downloads WASP](https://www.personalfab.it/en/downloads-2/download-info/firmware-powerwasp/)
 - [Previous IDE Releases - Arduino 1.6.x, 1.5.x BETA](https://www.arduino.cc/en/Main/OldSoftwareReleases#1.5.x)

## Marlin
This is a modded version from the newest 1.1.9 Marlin firmware release. This version can be compiled also with newer versions of Arduino (1.8.7+).

See also:
 - [MarlinFirmware/Marlin at 1.1.9](https://github.com/MarlinFirmware/Marlin/tree/1.1.9)
 - [Arduino - Software](https://www.arduino.cc/en/Main/Software)

### KNOWN BUGS:
 - Arduino 1.8.7 has a serious bug where the internal Java runtime locks up and stresses at least one CPU core at 100%. Use instead a hourly build that has an updated Java runtime.
