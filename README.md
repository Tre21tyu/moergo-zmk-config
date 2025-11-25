# Moergo Glove80 ZMK Configuration

Custom ZMK firmware configuration for the Moergo Glove80 keyboard.

## Features

- **Homerow Mods**: Custom hold-tap behavior with 500ms timeout
  - Left hand: Shift (A), Alt (S), Ctrl (D), GUI (F)
  - Right hand: GUI (J), Ctrl (K), Alt (L), Shift (;)
- **Vim-style Arrow Keys**: Arrow keys on Lower layer match Vim bindings (K=up, J=down)
- **Three Layers**: Base, Lower, and Magic

## Building Firmware

To build the firmware, push changes to GitHub and the firmware will be automatically built via GitHub Actions.

## Installation

Flash the generated `.uf2` file to your Glove80 keyboard.
