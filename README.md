# Cordillera

![Creative Commons License](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)

![PCB Render](https://i.imgur.com/AE0u5zm.png)

## About

The Cordillera PCB is an open design PCB heavily based on the Alice PCB. The only breaking change is the USB connector which renders it unusable on most Alice cases.

- STM32F072 controller
- USB C connector mounted at the bottom
- ESD, over voltage, and over current protection circuits
- Dual common cathode diodes instead of single ones
- Backlight, single color
- Fancy "press to reset, hold for bootloader" reset circuit
- Unused pins are broken out

## Dependencies

Symbols and footprints used are from my [KiCad library](https://github.com/coarse/KiCad-Keeb-Lib)

## Notes

- Due to the design having the USB C connector mounted at the bottom, the design cannot be used on most Alice cases.
- For acrylic sandwich Alice cases, you may be able to swap layers around to be able to use this design.

## Disclaimer

I provide this design as a reference for designing similar keyboard layout PCBs. Using them within your projects will require a will to do research of one's own and to learn the workings of them, potentially fixing issues if they exist.

I present the design as-is and as-available, without liability and without any guarantees regarding functionality, as expressed in the license. 
