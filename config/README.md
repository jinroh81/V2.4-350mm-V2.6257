[fans]

nhk:gpio5   Hotend Fan                     24v     1p. 40x40x10

nhk:gpio6   Extruder Fan (Part Cooling)    24v     1p. Blower 50x50x15

PD12        Nevermore                      24v     2p. Blower 50x50x15

PD13        Case Fan / Filter              12v     1p. 60x60x20

PD14        Fan Electric Carbinet I        12v     2p. 60x60x20

PD15        Fan Electric Carbinet II       12v     2p. 60x60x20

[thermistor]

PF3         Heater_Bed                     Generic 3950

nhk:gpioO29 Extruder Temp                  Generic 3950

PF5         Case/Filter                    Generic 3950

PF6         Electro Cabinet                Generic 3950

PF7         Under the Bed Nevermore        Generic 3950

[heater]

nhk:gpio9   heater tool

PA3         heater bed

[leds]

nhk:gpio7   SB Leds

PB10        Chamber Light

[homing]

PG6         Endstop X (Sensoreless DIAG PIN)

PG9         Endstop y (Sensoreless DIAG PIN)

nhk:gpio10   TAP Probe

[extruder]

step_pin: nhk:gpio23

dir_pin: nhk:gpio24

enable_pin: !nhk:gpio25

uart_pin: nhk:gpio0

tx_pin: nhk:gpio1
