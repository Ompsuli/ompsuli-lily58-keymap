# ompsuli-lily58-keymap
This my is keymap for lily58 rev1 split keyboard

## Installation

### Download tools

1. Download tools
  - [QMK MSYS](https://msys.qmk.fm/) for creating keymap file for your keyboard.
  - [QMK Toolbox](https://qmk.fm/toolbox) for flashing keyboard.
  - Open QMK MSYS and setup it.
```
qmk setup
"Clone qmk_firmware [y/n]: y
```

2. Clone files
On Windows:
```
cd %USERPROFILE%\qmk_firmware\keyboards\lily58\keymaps
git clone https://github.com/Ompsuli/ompsuli-lily58-keymap.git
```

3. Create keymap file
  - Open QMK MSYS
  - Write `qmk compile -kb qmk_firmware/keyboards/lily58/rev1 -km ompsuli-lily58-keymap`

4. Flash your keyboard
   - Open QMK Toolbox
   - Choose HEX-file (My path: %USERPROFILE%/qmk_firmware/lily58_rev1_default.hex
   - Press Flash
