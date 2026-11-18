# LED displays and Fault methodology

A 12V trigger system was originally considered, but later rejected as it adds complexity without sound benefit.
The preamp and power amplifiers will be housed in a cabinet so they won't be far apart - it is easy to acccess them to turn them on individually.
So the power and LED methodology can be simple and old school.

## Mezmerize preamp

- On-off push button (illuminated red ring) latching on front panel.  
- Not too bright, I'm sitting opposite
- Remains depressed when on, so tactile.
- Main use as a visual prompt/reminder to turn it off sound system not in use.
- No fault detection in preamp
- IEC connector in rear, incorporating suitably rated fuse. 
- No switch at rear.

## Wolverine

### Protection Philosophy

Protect it as fully as practical, but minimise external displays.

Fault display on the front panel would be good in some ways, but I'd hope to not need it. It adds to build complexity.  So: 

- There is no fault display on the front panel.
- But protection is given for speaker "out" over-voltage, over-current (speaker protection board)
- Over-temperature protection is given via the speaker protection board - e.g using 75 C NC bimetal thermal switches atttached to the heatsinks.
- If the heatsink temperature exceeds the defined protection threshold, the amplifier output is disabled and a dedicated LED fault indicator appears on the internal board.
- If the speaker protection fault triggers, the amplifier output is disabled and a dedicated LED fault indicator appears on the internal board.
- If the amp is systemically not operating normally after a cool down, I go into diagnostics mode, take the cover off, power up and look to see which internal fault LED lights under power.


### Power Control
- The primary purpose of the LED in the front panel push button is to tell me the amp is on, reminding me to turn it off if I am not using it.
- A front-panel push button (latched ) controls amplifier operation via the soft-start circuit.

An IEC inlet with integral fuse is fitted to the rear panel. No rear-panel power switch is required, as the amplifier will be installed within a cabinet where rear access is limited.
The switch would simply be on all the time
However, if I'm using the Deluxe chassis, I'd need to use one with a rear panel switch so the IEC unit fits the cutout.

### Status Indication

- On-off push button (illuminated red ring), latched, on front panel.
- Not too bright, I'm sitting opposite. 
- Remains depressed when on, so tactile.
- The LED extinguishes whenever the amplifier is switched off.
- If the button is depressed, illuminated, but there is no sound when playing music, a fault of some kind has occurred.



