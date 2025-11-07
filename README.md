# Klipper-Backup 💾 
Klipper backup script for manual or automated GitHub backups 

This backup is provided by [Klipper-Backup](https://github.com/Staubgeborener/klipper-backup).
___
Feel free to use my config to start your own!
Do note though, my printer is tuned to my own hardware and slicer configurations so adjust it to your own needs.
Also my printer is just tuned and maintained really well so mine can run at 18-minute-benchy speeds but yours might not.

Hardware mods:
- BigTreeTech SKR Mini E3 V3 mainboard
- Old Netbook running Debian as a host
- [Custom fan duct](https://www.printables.com/model/1329271-mini-satsana-with-dual-5015-blower-fans-for-ender) - Dual Winsinn 5015 part cooling, Sunon 4020 heat break
- Creality metal extruder arm replacement
- Capricorn XS bowden tube
- Yellow bed springs
- Spool holder on the side extrusion instead of top (less strain for brittle filaments but lower max z height)
- TP-Link Kasa HS103 smart outlet printer power switch

Notable Orca Slicer settings:
- Adaptive pressure advance
- Single extruder manual multi-material
- Manual colour change gcode (M600)
- Start/end gcode macros

Misc stuff:
- [Klipper TMC Autotune](https://github.com/andrewmcgr/klipper_tmc_autotune) - performance profile tuned to my stock motors for lower noise
- LCD menu item changes
- fun LCD status icons and layout :)
- ADXL345 + RPi Pico for input shaper (only connected during calib, config lines usually commented out)

Originally based off [Creality Ender 3 Pro](https://github.com/Klipper3d/klipper/blob/master/config/printer-creality-ender3pro-2020.cfg) and [generic BTT SKR Mini E3 V3](https://github.com/Klipper3d/klipper/blob/master/config/generic-bigtreetech-skr-mini-e3-v3.0.cfg) Klipper example configs
