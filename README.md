# Keychron K2 QMK custom firmware

This repo contains bins for QMK for the K2v2 keyboard, flash using Sonix QMK Flasher and [this repo](https://github.com/SonixQMK/qmk_firmware)

## Binaries

See the releases page for the goods

## Foreword

You **MUST** use Via 2.0.5, it is not compatible with Via 3. I might fix this down the track eventually. Via releases are [here](https://github.com/the-via/releases/releases)

Please keep in mind that you will lose Bluetooth capability with this. If you plan on using this long term, it may be worth opening the keyboard and detaching the battery

This is **NOT** compatible with the ISO layout of the K2v2, you can try it but YMMV. It may be better to instead [build the binary yourself](https://www.bradleynewman.dev/tutorials/qmk-on-keychron-k-series-keyboards)

## Instructions

1. Flash `keychron_k2_rgb_ansi_via.bin` with Sonix QMK Flasher, you will need the keyboard in bootloader mode. Two pins need to be bridged, they are located under the spacebar
2. In Via, navigate to the Design tab, load the K2 definition `via_ansi.json`
3. Navigate back to the Configure tab and load the layout `brads-k2v2-ansi-layout.json`
4. Enjoy!

## Layout

### Normal Layer

The normal layer has the Delete button swapped for Insert and the RGB Mode button swapped for Delete

![Normal Layer](https://github.com/soda3x/k2-qmk/raw/main/norm_layer.png)

### Fn Layer

These are the mappings for when the Fn key is pressed

The number row becomes the Numpad

![Fn Layer](https://github.com/soda3x/k2-qmk/raw/main/fn_layer.png)

### Other Layouts

Feel free to use your own layout, I just included mine for my ease of access
