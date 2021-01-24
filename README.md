# Custom dwm config

Dwm is an extremely fast, small, and dynamic window manager for X. This is my own configuration file for access.

## Installation

### Arch

```bash
makepkg -cf
sudo pacman -U *.pkg.tar.xz
```

### Other linux

After cloning,

```bash
cd dwm-mt
sudo make clean install
```

## Keybinding

Mod key: `super` (windows)

## Configuring

If you want to configure, it is done by editing `config.h` and recompiling the source code.

```bash
sudo make install
```