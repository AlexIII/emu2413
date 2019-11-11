emu2413 v0.63.x
=======

A YM2413 emulator written in C.

This version is legacy v0.63 based, some critical envelope bugs and rhythm volume are fixed.

# Known Issue 
Ryhythm key-on flags (bit0-4 of reg:0x0e) and general channel key-on flags (bit4 of reg:0x20-0x28) are not shared. 
Lack of some rhythm sound can be found with a few drivers (ex. Microcabin)
This issue is solved master branch version of emu2413. See update_key_status function of it.