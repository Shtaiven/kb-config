# kb-config
Keyboard configuration files.

## Installation

```sh
python3 -m pip install --user qmk
qmk setup  # accept all prompts
```

## Flashing a keyboard

```sh
qmk install <path_to_qmk_firmware>  # get this from the VIA repo
# place keyboard in bootloader mode
# e.g. unplug -> hold ESC -> plug in
```

## Updating VIA keymap

* Open [VIA](usevia.app)
* Click on "SAVE + LOAD"
* Click on "Load"
* Choose the via \*.json config file
