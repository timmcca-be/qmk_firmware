# hotdox76

_An Ergodox style keyboard with per key RGB._

-   Keyboard Maintainer: [Drashna Jael're](https://github.com/Drashna Jael're)
-   Hardware Supported: Hotdox 76v2
-   Hardware Availability: https://github.com/Oh-My-Mechanical-Keyboard

Make example for this keyboard (after setting up your build environment):

    make hotdox76v2:default

Flashing example for this keyboard:

    make hotdox76v2:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

-   **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
-   **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
-   **Keycode in layout**: Press the key mapped to `RESET` if it is available

# RBG Matrix

```
,--------------------------------------------------.           ,--------------------------------------------------.
|   0    |   1  |   2  |   3  |   4  |   5  |  6   |           |  49  |  48  |  47  |  46  |  45  |  44  |   43   |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|   13   |  12  |  11  |  10  |   9  |   8  |  7   |           |  50  |  51  |  52  |  53  |  54  |  55  |   56   |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|   14   |  15  |  16  |  17  |  18  |  19  |------|           |------|  62  |  61  |  60  |  59  |  58  |   57   |
|--------+------+------+------+------+------|  20  |           |  63  |------+------+------+------+------+--------|
|   26   |  25  |  24  |  23  |  22  |  21  |      |           |      |  64  |  65  |  66  |  67  |  68  |   69   |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |  27  |  28  |  29  |  30  |  31  |                                       |  74  |  73  |  72  |  71  |  70  |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |  37  |  36  |       |  79  |   80   |
                                ,------|------|------|       |------+--------+------.
                                |      |      |  35  |       |  78  |        |      |
                                |  32  |  33  |------|       |------|   76   |  75  |
                                |      |      |  34  |       |  77  |        |      |
                                `--------------------'       `----------------------'
,--------------------------------------------------.           ,--------------------------------------------------.
|                                                  |           |                                                  |
|                  40                   41         |           |              84                83                |
|                                                  |           |                                                  |
|                                                  |           |                                                  |
|                                                  |           |                                                  |
|                                                  |           |                                                  |
|                  39                   42         |           |              85                82                |
|                                                  |           |                                                  |
|                                                  |           |                                                  |
|            38        ,---------------------------'           `-----------------------------.       81           |
|                      |                                                                     |                    |
|                      |                                                                     |                    |
|                      |                                                                     |                    |
|                      |                                                                     |                    |
|                      |                                                                     |                    |
`----------------------'                                                                     `--------------------'
```
