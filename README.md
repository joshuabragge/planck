# SIMAK planck layout

This is a colemak layout for the [Planck][planck]. This is optimized for SimCorp Business System Anaylst using Windows.

[planck]: https://olkb.com/planck 

## Table of Contents

* [Layouts](#layouts)
    - [Overview](#overview)
* [Building](#building)
* [Changelog](https://github.com/joshuabragge/planck-layout/blob/master/NEWS.md#readme)

# Layouts

## Overview

[![Overview](https://github.com/joshuabragge/planck-layout/blob/master/images/keyboard-layout.png)](http://www.keyboard-layout-editor.com/#/gists/4150d8a814edc6441cdcda4b3897e1ab)

This is a Colemak layout, heavily influenced by the greatst keyboard layout theorist of our time, [algernon][algernon] and his thrilling [blog][blog].

[algernon]: https://github.com/algernon/ergodox-layout
[blog]: https://asylum.madhouse-project.org/blog/tags/ergodox/

# Building

```
$ git clone https://github.com/qmk/qmk_firmware.git
$ cd qmk_firmware
$ git clone git@github.com:joshuabragge/planck-layout.git \
            keyboards/planck/keymaps/planck-jb
$ sudo make planck/rev6:planck-jb:dfu-util
