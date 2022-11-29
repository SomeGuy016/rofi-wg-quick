# rofi-wg-quick

A rofi wrapper for wg-quick
!(Showcase)[Resources/rofi-wg-quick_showcase.gif]

## Usage
Just run `rofi-wg-quick`.

Note: At the moment this utility assumes that all wireguard configuration files are in /etc/wireguard. This may be expanded upon later to allow for more customization. 

## Installation
I currently don't provide any real installation, just copy the script into whatever directory you feel like. I'd recommend adding said directory to the path if you plan on running it from the command line a lot. If there's enough interest I can create a PKGBUILD or a flatpak but it's just a single file. 

## Dependencies
* wireguard-tools
* rofi
* bash
* coreutils
* iproute2
* polkit
* sed

## License
This script is released under the MIT license. See `LICENSE` for more details. 
