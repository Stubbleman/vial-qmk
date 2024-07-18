# handwired/dactyle_manuform_lowprofile


A budget Dactyl-Manuform build using Raspberry Pi Pico. Modified from jankrp2040dactyl

* Keyboard Maintainer: [Jacob Wu](https://github.com/Stubbleman)
* Hardware Supported: RP2040 Community Edition
* Hardware Availability: https://www.digikey.com/en/product-highlight/r/raspberry-pi/raspberry-pi-picoboard

Make example for this keyboard (after setting up your build environment). Recommand vial:

    make handwired/dactyle_manuform_lowprofile:vial

Flashing example for this keyboard:

    make handwired/dactyle_manuform_lowprofile:vial:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
