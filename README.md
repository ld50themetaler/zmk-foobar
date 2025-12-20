# ZMK Configuration for The foobar Keyboard

Generated from QMK info.json

## Keyboard Information
- Name: The foobar Keyboard
- Type: Split
- Normalized Name: the_foobar_keyboard
- Board: ble_micro_pro

## Files Structure

### Split Keyboard Files
- boards/shields/the_foobar_keyboard/the_foobar_keyboard_left.overlay - Left side hardware definition
- boards/shields/the_foobar_keyboard/the_foobar_keyboard_right.overlay - Right side hardware definition
- boards/shields/the_foobar_keyboard/the_foobar_keyboard_left.conf - Left side configuration
- boards/shields/the_foobar_keyboard/the_foobar_keyboard_right.conf - Right side configuration

### Common Files
- boards/shields/the_foobar_keyboard/layouts.dtsi - Physical layout definition
- boards/shields/the_foobar_keyboard/Kconfig.defconfig - Default configuration
- boards/shields/the_foobar_keyboard/Kconfig.shield - Shield configuration
- boards/shields/the_foobar_keyboard/the_foobar_keyboard.zmk.yml - ZMK metadata
- boards/shields/the_foobar_keyboard/the_foobar_keyboard.keymap - Shield keymap include
- config/keymap.keymap - Keymap definition
- config/info.json - Keyboard layout information for keymap editors
- config/west.yml - West manifest for ZMK dependencies
- build.yaml - Build configuration for ZMK
- zephyr/module.yml - Zephyr module configuration
- .github/workflows/build.yml - GitHub Actions workflow for building firmware

## Usage
1. Copy all files to your ZMK config repository
2. Customize the keymap in config/keymap.keymap as needed
3. Push to GitHub to trigger automatic firmware builds

## Board Information
This configuration is set up for ble_micro_pro. The board is from sekigon-gonnoc's repository.
