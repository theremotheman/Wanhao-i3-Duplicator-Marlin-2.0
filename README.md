After reading about thermal protection and how wanhao i3 default firmware handles thermistor failures I decided to find a modern alternative for original repetier firmware. It took me 3 days and many print failures to set everything right without sacrificing mesh bed leveling and s-curve.

As I took many posts and different versions of marlin configuration files to compile this 2.0.x remix - I'm giving my configuration.h and configuration_adv.h to the community for further modifications and enhancements.



Some pieces of information:

1. Heigh is set to 180mm

2. Thermistor table is set for a printer with a 4.7k resistor - if Your ambient values are wrong - use nitrogen777 thermistor table

3. Manual mesh bed leveling is enabled

4. SdCard support is disabled - use USB

5. Baudrate is set to 250 000

6. Enabled thermal protection (doh)

7. PID Settings are set for dii cooler but can be easily modified from the printer menu

8. EEPROM enabled

9. Enabled S_CURVE_ACCELERATION

10. The buzzer is set to a speaker so You can play little melodies after print finished

11. Some more?



Installation instructions: https://www.fission3d.com/guides/flash-bootloader-and-install-firmware-with-raspberry-pi
