# My Corne Keymap
This is the current layout that I'm using for my corne split keyboard

# Corne specs
- 3x6 key
- kb2040 MCU

# Compiling
This config is compiled using QMK firmware

## Compile command
Due to my MCU being the kb2040, the command I use to compile is below.
```
qmk compile -e CONVERT_TO=kb2040 -kb crkbd -km elementrix08
```
Where elementrix08 is the name of my configuration.
