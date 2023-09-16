# ModEleSys PSU
ModEleSys 1x1 module Powersupply. One DC input that is fed into a LD1117 LDO, then railsplit with a LM317/LM337 railsplitter, this creates a virtual earth, another LD1117 is present to create a 5V supply, and it uses this virtual ground.
## TODO's
Still some things need to be done:
* Schematic entry
* Place and route
* Review
* Production
* Assemble
* Test & characterise
* update Readme.md with pictures and BOM
## BOM
This is a list of hardware components. If just mentioned a generic component like a 1K 0402 resistor, just name it as such, free to substitute. If you need some special integrated IC's show some sources like Mouser, Digikey, Farnell, or LCSC
* D2PAK (TO-252) LD1117, LM317 and LM337
* SMA cased diodes
* Mostly ceramic capacitors used
* 500mA trip polyfuses in 1812 SMT housing
