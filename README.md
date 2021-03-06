### What is this?

![Tougher INA3221 power meter 3D side view.](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/photos/tougher-power-meter-v1.0-top.jpg "Assembled Tougher Power Meter Top View")

Power monitor with three channels, each capable of continuous 10A and 24V. It is compatible with both Arduino and Feather, and is based on a popular INA3221. The power monitor is more robust compared to other modules based on this IC. Each channel has proper RC filtering with TVS diodes to prevent INA3221 from being destroyed by transients, and to eliminate glitches. Pluggable screw terminals are rated for 15A, and can handle 12 to 30 AWG wires.

The third channel has a TPS1HB08A power switch, to be able to disconnect the load.
The board can also provide power to the Feather or Arduino from the first channel via a built-in buck converter.

### Block diagram

![Tougher INA3221 Power Meter Block Diagram](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/block-diagram/TougherPowerMonitor-block-diagram.png?raw=true "block diagram")

### Schematics

![Tougher INA3221 Power Meter Schematics](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/schematics/TougherPowerMonitor-schematics-main.png?raw=true "schematics")

![Current sense resistor with RC filtering and TVS diodes.](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/schematics/TougherPowerMonitor-schematics-current-sense-frontend.png?raw=true "schematics")

![Schematics of AP63205 buck converter.](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/schematics/TougherPowerMonitor-schematics-buck.png?raw=true "schematics")

![Schematics of TPS1HB08 high-side power switch.](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/schematics/TougherPowerMonitor-schematics-power-switch.png?raw=true "schematics")

### Assembled board

![Assebmbled Tougher Power Meter (bottom view).](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/photos/tougher-power-meter-v1.0-bot.jpg "Assembled Tougher Power Meter Bottom View")
![Assebmbled Tougher Power Meter (side view).](https://github.com/beast-devices/TougherPowerMonitor-HW/blob/master/photos/tougher-power-meter-v1.0-side.jpg "Assembled Tougher Power Meter Side View View")