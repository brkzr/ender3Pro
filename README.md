## Marlin 3D Printer Firmware 

Version 1.1.9.1

BLTouch probe defined

``` c
x: -40, y = -12, z= -1.65
```

After setup, the following line should be added to the starting code on the slicer (_cura -> machine settings_)

``` gcode
; Ender 3 Custom Start G-code
G92 E0 ; Reset Extruder
G28 ; Home all axes
G29; BLTouch Bed Level
```


[BLTouch Mount](https://www.thingiverse.com/thing:3584158) : 

![ ](/Images/mount.jpg)