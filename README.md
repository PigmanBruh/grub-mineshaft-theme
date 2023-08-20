# grub-mineshaft-theme

This is yet another Minecraft-Themed GRUB theme, but despite i'm using [Mine-Imator](https://www.mineimator.com/) to make the backgrounds, it barely resembles Minecraft style because i used a photo-realistic texture packs

## Installation

1. Clone this repository

        git clone https://github.com/PigmanYT3531/grub-mineshaft-theme.git

2. (Optional) Pick the background from the `alternate` folder (not available yet), or you can even render the background yourself with the included project file (texture pack not included)
3. Paste the theme to GRUB's theme folder (`/boot/grub/themes`), remember to paste the entire folder, not just the `theme.txt`
4. Open `/etc/default/grub`, find and modify these lines

        # Uncomment one of them for the gfx desired, a image background or a gfxtheme
        #GRUB_BACKGROUND="/path/to/wallpaper"
        GRUB_THEME="/boot/grub/themes/grub-mineshaft/theme.txt"

5. Generate your GRUB config

        sudo grub-mkconfig -o /boot/grub/grub.cfg

## Credits

[Distro Grub Theme](https://github.com/AdisonCavani/distro-grub-themes) : The base of this theme, and a lot of icons

## Texture Pack Used

[Stratum](https://continuum.graphics/stratum-resourcepack)

## Screenshot

![Screenshot](https://github.com/PigmanYT3531/grub-mineshaft-theme/assets/87263998/dfac2835-22d0-4ee9-8abf-7975abecf9ce)
Rendered with Stratum texture pack, previewed with [grub2-theme-preview](https://github.com/hartwork/grub2-theme-preview)
