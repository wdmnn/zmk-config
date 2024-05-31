# Hillside ZMK firmware

![hillside](https://i.ibb.co/tqh33LV/PXL-20240531-063437872.jpg)

[![Build](https://github.com/wdmnn/zmk-config/actions/workflows/build.yml/badge.svg)](https://github.com/wdmnn/zmk-config/actions/workflows/build.yml)

This is the [ZMK](https://zmk.dev/docs) firmware
 for the [Hillside](https://github.com/mmccoyd/hillside) family of split ergonomic keyboards.

It contains keymap definition files for three boards in [./config](./config):

 - Hillside 46 with 3x6+5 keys

Pushing changes will build all the keyboards. You need to be signed in to a GitHub account to push changes and build the firmware. To not waste build time, comment out the keyboards in [./build.yaml](./build.yaml) that you do not have.

To build the firmware:

- Fork this repo on GitHub
- Clone your fork locally
- Trigger a build:
  - Make a trivial change to ./build.yaml (or any non *.md file)
  - Push that change
- Look in the [Actions](https://github.com/wdmnn/zmk-config/actions) tab
     for the build triggered by that change. 
- Wait for the build to finish
- Click on the build link next to the green checkbox
- Download the artifact file with the firmware
- See [Installing The Firmware](https://zmk.dev/docs/user-setup#installing-the-firmware)
  for more details from there.

The keymap used is inspired by:

- [Markstos Corne keymap](https://mark.stosberg.com/markstos-corne-3x5-1-keyboard-layout/)
- [Kyria keymap](https://keymapdb.com/keymaps/default-kyria/)

...and can be found here:
- [./config/hillside46.keymap](./config/hillside46.keymap)

A keymap editor can be found here:
- [Keymap editor](https://nickcoutsos.github.io/keymap-editor)

There is also a [JSON](./config/hillside-46.json) for [Keyboard layout editor](http://www.keyboard-layout-editor.com/#/)

Pushing the change will trigger a build as above.

If you want to enable features,
  modify the appropriate ./config/hillside*.conf file.

The Hillside shield definition files should *not* need to be modified and are in ./config/boards/shields.
