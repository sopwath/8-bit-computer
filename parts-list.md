# Parts Lists

Each module of the entire computer has a list of components. I'll try to split them out here.

## Generic Component Notes

Dave Jones' EEVblog has some videos about component selection. I need to find the specific ICs for this project as there are several variations for each component.




## Clock module

Parts Needed:
- 3	xx555 Timer ICs
  - NE555P will work fine.
- 1	74LS04 Hex inverter
- 1	74LS08 Quad 2-input AND gate
- 1	74LS32 Quad 2-input OR gate
- 1	Momentary tact switch
  - Finding these with leads long enough for a breadboard are tough.
  - You need more than a through-hole model, something marked as wire-wrap may be more appropriate
  - I found the Omron brand, B3F series, with tape-reel leads that are extra long: https://www.digikey.com/en/products/detail/omron-electronics-inc-emc-div/B3F-6000/31447
- 1	SPST slide switch
  - The ones that came with the kit are too big to fit in the breadboard.
  - There are so many options available online, but I bought a bunch with the leads specifically marked 0.1" apart: https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/450301014042/5209104
- 1 1MOhm, potentiometer
  - Again, these are tough to find in a through hole model with leads long enough for a breadboard.
  - Something like this might work: https://www.digikey.com/en/products/detail/bourns-inc/3352T-1-105LF/1088343
  - 

## Registers and ALU

Parts Needed:
- 2	74LS86 Quad XOR gate
- 6	74LS173 4-bit D register
- 4	74LS245 8-bit bus transceiver
- 2	74LS283 4-bit binary adder

## RAM and Program counter

Parts Needed:
- 1	74LS00 quad NAND gate
- 2	74LS04 hex inverter
- 4	74LS157 quad 2-1 line mux
- 1	74LS161 4-bit binary counter
- 1	74LS173 4-bit D register
- 2	74189 64-bit RAM
- 2	74LS245 8-bit bus transceiver
- 1	Momentary tact pushbutton
- 1	SPDT slide switch
- 1	4-position DIP switch
- 1	8-position DIP switch

## Output and control logic

Parts Needed:
- 1	Arduino nano clone* (for building the EEPROM programmer)
- 1	LM-555 IC timer
- 1	74LS00 quad NAND gate
- 1	74LS02 quad NOR gate
- 2	74LS04 hex inverter
- 2	74LS08 quad AND gate
- 1	74LS107 dual J-K flip-flop
- 1	74LS138 3-to-8 line decoder
- 1	74LS139 2-to-4 line decoder
- 1	74LS161 4-bit counter
- 1	74LS173 4-bit D register
- 1	74LS273 8-bit D register
- 2	74HC595 8-bit shift register
- 3	28C16 EEPROMs
- 1	Momentary tact pushbutton
- 1	SPDT slide switch
