# Alexandrie_V2

Kicad files

Control board for Alexiares filter set driven by an Orion/OrionMK2/Anvelina SDR board with dual 16 bits ADC

This second version drives a dual RX BPF filter, no 10 dB step attenuator

This work is protected by the TAPR Open Hardware Licence https://www.tapr.org/ohl.html

Original work by Graham Haddock, KE9H and Phil Harman, VK6APH.

This board supports the I2S "Alexiares" protocol (also called "J16") of 
the original Hermes SDR board designed by the OpenHPSDR group.

When the board is fully populated, it is compatible with the Orion/Anvelina frontend (one LPF, two BPF)

As the third generation of Alexiares frontend is not sold by Apache but still under an open hardware licence, a new and more "modular" 
design was needed by many hams wishing to build a "Orion class" fontend
( for Homebrewed Hermes,  Angelia, Red Pitaya boards supporting Pavel Demin's firmware, Odyssey2 SDR, please use the original Alexandrie pcb ) 


3D image of the board are stored on this repo

Alexandrie_V2_dwn.jpg

Alexandrie_V2_up.jpg

A common Gerber set of files will be used for both filters (one with a "RX2_GND" relay, one with a strap on the relay footprint)

This board could also be used with the new Aries ATU/Zolotarev lpf/Munin400 high power frontend

