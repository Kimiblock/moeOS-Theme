# moeOS.Config

---

![Logo](https://raw.githubusercontent.com/Kimiblock/moeOS.config/master/usr/share/icons/hicolor/scalable/apps/moeos.svg)

Arch Linux w/ Gnome Wayland only, use at your own risk.

# Installation

```
cd ~
git clone https://github.com/Kimiblock/moeOS-Package.git
cd moeOS-Package
paru -Ui #or, alternatively makepkg -si
```

# Ingredients

Contains the following configurations and customizations:

- moeOS Plymouth boot splash theme.

- Default `sbupdate` Secure Boot configurations, an `mkinitcpio` preset, cmdline / fstab example, `sleep.conf`, `Packagekit.conf`.

- `lsb-release` and `os-release` replacement.

- A hook to replace files automatically.

- A moeOS icon and splash image

- A kvantum theme looks like libadwaita applications with blur and transparent enabled.

- Some handy scripts eg. `v2hevc` `v2avc` `oggaudio` to transcode video footages and audio files quickly using VA-API.

- Some powersave settings.

- A default tlp configuration file.

- A default mpv config file w/ modern interface and hardware acceleration.

- A default fontconfig file. Preferred fonts are Inter fonts, Noto fonts.

- Networkmanager connectivity test pointed to `blog.kimiblock.top`

- Colors:
  
  - Bright: Accent: `#ed65e2`; Background: `#ed65e2`
  
  - Dark: Accent: `#ed65e2`; Background: `#da7de3`

# Rime configuration, Celluloid and Flatpak fonts
Should work out of the box.

# Switchable Graphics
With `moeOS`, you must install Software natively (Not Flatpak) and execute `prime-run` wrapper script to offload applications on your discreate graphics card.
