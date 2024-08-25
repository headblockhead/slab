# The Slab Keyboard
A fully-featured collection of my designs for an [**ortholinear**](https://en.wiktionary.org/wiki/ortholinear), [**hotswap**](https://en.wikipedia.org/wiki/Keyboard_technology#Hot-swappable_keyboard), [**MX switch**](https://en.wikipedia.org/wiki/Keyboard_technology#Metal_contact) custom mechanical keyboard featuring an [**128x32 pixel OLED display**](https://en.wikipedia.org/wiki/OLED#), a [**rotary encoder**](https://en.wikipedia.org/wiki/Rotary_encoder) and [**90 individually-addressable RGB LEDs**](https://en.wikipedia.org/wiki/Light-emitting_diode#Strip).

![slab keyboard with rainbow animation and oled running](https://github.com/user-attachments/assets/d2a1c952-e986-4887-a9cd-9fdd5c0791ee)

## [The Firmware](https://github.com/headblockhead/slab-firmware)

The keyboard uses a [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html) as the microcontroller of choice. The firmware is written in C, and uses the pico SDK, as well as my [SQUIRREL library](https://github.com/headblockhead/SQUIRREL).

See [slab-firmware](https://github.com/headblockhead/slab-firmware) for the downloads, and documentation.

## [The Software](https://github.com/headblockhead/OpenRGB)

The keyboard is controlled by OpenRGB only at the moment. Key remapping may be added into a seperate program later. I maintain [my own fork of OpenRGB](https://github.com/headblockhead/OpenRGB) that has the Slab added as a device. If the project gets enough attention, I might submit a PR to OpenRGB on gitlab, so it is added to the main version as well.

## The Hardware

The keyboard has a [custom PCB](https://github.com/headblockhead/slab-pcb) and [3D-printable case](https://github.com/headblockhead/slab-case). Follow the links to find out more.

## Showcase
[![4 pictures of the Slab Keyboard with a USB cable plugged in, with a play button in the center](https://github.com/user-attachments/assets/123dee2b-938f-46e1-b888-c03c419481f0)](https://www.youtube.com/watch?v=I5xrWIB_Eh8)
