# rd-k617-mods
My modifications for Redragon K617 Keyboard.

# Modifications
`Cfg.ini` contains the following remaps:
- Colemak keyboard Layout
- Remaps "App" key (the key on the right side of the FN key) as backspace.
- Capslock key as Left Control key.
- Left Control key as another FN key.
- FN layer keys
  - x as backspace
  - u as prev media
  - y as next media
  - n as vol low
  - e as vol up
  - b as mute media
  - k as play-pause media

`colemak.bk` is a profile for K617 software that remaps:
- Colemak keyboard layout.
- Remaps "App" key (the key on the right side of the FN key) as backspace.

> [!NOTE]
> `Cfg.ini` and `colemak.bk` are not intended to be used together.
# Extras
`Cfg-stock.ini` is the stock configuration file.

# How To Apply
> [!IMPORTANT]
> Make sure you have the personalisation software installed from [here](https://cdn.shopify.com/s/files/1/2695/9506/files/Redragon_K617-RGB_Setup.exe?v=1658806701).

Head over to installation directory at `C:\Program Files (x86)\Redragon K617-RGB`. Then replace the `Cfg.ini` file with the one in this repository. Once done, click on `KeyboardDrv.exe` then click `Restore` and `Apply`. 

Either do that or just open the software then import and apply the profile `colemak.bk` (very limited compared to `Cfg.ini`).

> [!NOTE]
> The software seems to load the configuration file in memory, so make sure to restart the app after making changes to the `Cfg.ini` file.

# Credits
- [redragonKB-remap](https://github.com/octenite/redragonKB-remap/)
