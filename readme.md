# Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/qmk)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the Clueboard product line.

## Ruben's Keyboard Keymaps

These are my custom keymaps for the Planck, Lily58, and Tokyo60 keyboards. Each link opens the keymap files in this repository.

### Planck

The Planck keymap includes QWERTY, Colemak, and gaming base layers, along with numeric, function, and navigation layers.

Keymap: [Planck — rubangarmon](https://github.com/rubangarmon/qmk_firmware/tree/master/keyboards/planck/keymaps/rubangarmon)

Build:

```sh
qmk compile -kb planck/rev6 -km rubangarmon
```

Flash:

```sh
qmk flash -kb planck/rev6 -km rubangarmon
```

### Lily58

The Lily58 keymap includes QWERTY, numeric, function, and navigation layers, plus OLED status and key logging.

Keymap: [Lily58 — rubangarmon](https://github.com/rubangarmon/qmk_firmware/tree/master/keyboards/lily58/keymaps/rubangarmon)

Build:

```sh
qmk compile -kb lily58/rev1 -km rubangarmon
```

Flash:

```sh
qmk flash -kb lily58/rev1 -km rubangarmon
```

### Tokyo60

The Tokyo60 keymap includes Windows/Linux and Mac base layers, function and movement layers, and RGB controls.

Keymap: [Tokyo60 — rubangarmon](https://github.com/rubangarmon/qmk_firmware/tree/master/keyboards/tokyokeyboard/tokyo60/keymaps/rubangarmon)

Build:

```sh
qmk compile -kb tokyokeyboard/tokyo60 -km rubangarmon
```

Flash:

```sh
qmk flash -kb tokyokeyboard/tokyo60 -km rubangarmon
```

Run these commands from the QMK firmware repository root. Put the keyboard into bootloader mode when prompted to flash it.

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [VitePress](https://vitepress.dev/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls).