# Hillside ZMK firmware

![hillside](https://i.ibb.co/tPCbQfF/hillside-46.png)

[![Build](https://github.com/wdmnn/zmk-config/actions/workflows/build.yml/badge.svg)](https://github.com/wdmnn/zmk-config/actions/workflows/build.yml)

This is the [ZMK](https://zmk.dev/docs) firmware
 for the [Hillside46](https://github.com/wdmnn/hillside) split ergonomic keyboard.

The keymap definition file for the board in [./config](./config):

 - Hillside 46 with 3x6+5 keys

The keymap used is inspired by:

- [Markstos Corne keymap](https://mark.stosberg.com/markstos-corne-3x5-1-keyboard-layout/)
- [Kyria keymap](https://keymapdb.com/keymaps/default-kyria/)

...and can be found here:
- [./config/hillside46.keymap](./config/hillside46.keymap)

A keymap editor can be found here:
- [Keymap editor](https://nickcoutsos.github.io/keymap-editor)

There is also a [JSON](./config/hillside-46.json) for [Keyboard layout editor](http://www.keyboard-layout-editor.com/#/)

Pushing a change will trigger a build and the firmware will be available from the Actions tab.

If you want to enable features,
  modify the appropriate ./config/hillside*.conf file.

The Hillside shield definition files should *not* need to be modified and are in ./config/boards/shields.
