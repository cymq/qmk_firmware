# runagate

35% keyboard

* Keyboard Maintainer: [cymq](https://github.com/cymq)
* Hardware Supported: Runagate Main PCB V1(RP2040)
* Hardware Availability: It's not available for sale now, but if you contact me, I'll send production file to you :D

Make example for this keyboard (after setting up your build environment):

    make runagate:default

Flashing example for this keyboard:

    make runagate:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
