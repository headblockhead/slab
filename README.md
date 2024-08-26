# The Slab Keyboard
My full designs for an [**ortholinear**](https://en.wiktionary.org/wiki/ortholinear), [**hotswap**](https://en.wikipedia.org/wiki/Keyboard_technology#Hot-swappable_keyboard), [**MX switch**](https://en.wikipedia.org/wiki/Keyboard_technology#Metal_contact) custom mechanical keyboard featuring an [**128x32 pixel OLED display**](https://en.wikipedia.org/wiki/OLED#), a [**rotary encoder**](https://en.wikipedia.org/wiki/Rotary_encoder) and [**90 individually-addressable RGB LEDs**](https://en.wikipedia.org/wiki/Light-emitting_diode#Strip).

![slab keyboard with rainbow animation and oled running](https://github.com/user-attachments/assets/d2a1c952-e986-4887-a9cd-9fdd5c0791ee)

## [The Firmware](https://github.com/headblockhead/slab-firmware)

I chose a [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html) as the microcontroller, as it has a very small footprint, and adding an rp2040 directly to the PCB would have introduced too many issues with soldering; I want this board to be easy to make! *Maybe* I'll make a V2 someday with a chip directly on-board. 

The firmware is written in C, and uses the [Pico SDK](https://github.com/raspberrypi/pico-sdk), as well as [my own SQUIRREL library](https://github.com/headblockhead/SQUIRREL).
See [slab-firmware](https://github.com/headblockhead/slab-firmware) for the downloads, and documentation.

## [The Software](https://github.com/headblockhead/OpenRGB)

The keyboard is controlled by OpenRGB only at the moment. Key remapping may be added into a seperate program later. I maintain [my own fork of OpenRGB](https://github.com/headblockhead/OpenRGB) that has the Slab added as a device. OpenRGB can control almost every single RGB device there is, so it made sense to implement the RGB control directly into OpenRGB, for maximum compatibility. If the project gets enough attention, I might submit a merge request to OpenRGB on gitlab, so it is added to the main version as well.

## The Hardware - PCB and case

I have made a [custom PCB](https://github.com/headblockhead/slab-pcb) and [3D-printable case](https://github.com/headblockhead/slab-case) for the keyboard. Follow the links for more detail!

## Want to build it yourself?

Firmware downloads are available in [slab-firmware](https://github.com/headblockhead/slab-firmware/releases), 3D-print files can be found [under exported-stl in slab-case](https://github.com/headblockhead/slab-case/tree/main/exported-stl), and a bill-of-materials is included in [slab-pcb](https://github.com/headblockhead/slab-pcb).

## Want to contribute?

The software you will need to contribute is [Nix](nixos.org). Nix is an advanced, reproducible, and declarative package manager. Most repos that I work in use a `flake.nix` file for development, building and sometimes testing. Use `nix develop` to get started contributing, then submit a pull request with your new additions.

## Showcase
[![4 pictures of the Slab Keyboard with a USB cable plugged in, with a play button in the center](https://github.com/user-attachments/assets/123dee2b-938f-46e1-b888-c03c419481f0)](https://www.youtube.com/watch?v=I5xrWIB_Eh8)
