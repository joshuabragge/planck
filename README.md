# planck
Custom firmware for the olkb's planck keyboard


# Building

```
$ git clone https://github.com/qmk/qmk_firmware.git
$ cd qmk_firmware
$ git clone https://github.com/joshuabragge/ergodox \
            keyboards/planck/keymaps/planck-jb
$ make planck/rev6:planck-jb:dfu-util
