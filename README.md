# rd-k617-mods
My modifications for Redragon K617 Keyboard.

# Modifications
`Cfg.ini` contains the following remaps:
- Caplock key as Left Control key.
- Left Control key as another FN key.

`colemak.bk` is a profile for K617 software that implements Colemak keyboard layout. It also:
- Remaps "App" key (the key on the right side of the FN key) as backspace.

# Extras
`Cfg.stock.ini` is the stock configuration file.

# How To Apply
> [!IMPORTANT]
> Make sure you have the personalisation software installed from [here](https://cdn.shopify.com/s/files/1/2695/9506/files/Redragon_K617-RGB_Setup.exe?v=1658806701).

Head over to installation directory at `C:\Program Files (x86)\Redragon K617-RGB`. Then replace the `Cfg.ini` file with the one in this repository. Once done, click on `KeyboardDrv` then click `Restore` and `Apply`, then import the profile `colemak.bk`.

> [!NOTE]
> The software seems to load the configuration file in memory, so make sure to restart the app after making changes to the `Cfg.ini` file.
