# Installation
1. Download the theme files from the 'Releases' section.
2. Copy the theme folder into your EFI partition under `EFI/OC/Resources/Image`.
3. Rename the correct `Background_<resolution>.icns` to `Background.icns` according to your display.
4. Update your `config.plist` to use the new theme. 
    - `Misc -> Boot -> PickerMode` : `External`
    - `Misc -> Boot -> PickerAttributes` : `17`
    - `Misc -> Boot -> PickerVariant` : `Etho\Nordic`

Check this [guide](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html) and the [OpenCanopy documentation](https://dortania.github.io/docs/latest/Configuration.html#opencanopy) for further information.