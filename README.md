# Alexandrie_V2

Dual ADC OpenHPSDR frontend control board

Kicad files

* Control board for Alexiares filter set driven by an Orion/OrionMK2/Anvelina SDR board with dual 16 bits ADC

![aka "Alexandrie V2](https://github.com/F6ITU/AlexV2/blob/main/AlexV2_front.jpg)

This board supports the SPI "Alexiares" protocol (also called "J15") of 
the original Hermes SDR board designed by the OpenHPSDR group.

This second version drives a dual RX BPF filter. 
It also remains compatible with older versions of Alex (see assembly notes

As the third generation of Alexiares frontend is not sold by Apache but still under an open hardware licence, 
a new and more "modular" design was needed by many hams wishing to home-build a "Orion class" fontend

A common Gerber set of files will be used for both RX filters (one with a "RX2_GND" relay, one with a strap on the relay footprint)

TX filter depends on user's choice. The original 150W Alexiares lpf (https://github.com/F6ITU/Alexiares_LPF)
or LA2NI Zolotarev 600W LPF (https://github.com/LA2NI/Zolotarev-LPF)
This board could also be used with the new Aries ATU/Zolotarev lpf/Munin400 high power frontend

This work is protected by the TAPR Open Hardware Licence https://www.tapr.org/ohl.html
Original work by Graham Haddock, KE9H and Phil Harman, VK6APH.