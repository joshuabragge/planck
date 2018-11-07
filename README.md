# planck
Custom firmware for the olkb's planck keyboard


# Building

```
$ git clone https://github.com/qmk/qmk_firmware.git
$ cd qmk_firmware
$ git clone git@github.com:joshuabragge/planck.git \
            keyboards/planck/keymaps/planck-jb
$ make planck/rev6:planck-jb:dfu-util
