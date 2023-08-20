# grub-mineshaft-theme

This is yet another Minecraft-Themed GRUB theme, but despite i'm using Mine-Imator to make the backgrounds, it barely resembles Minecraft style because i used a photo-realistic texture packs

### Installation

1. Clone this repository
2. (Optional) Pick the background from the `alternate` folder, or you can even render the background yourself with the included project file in different resolution
3. Paste the theme to GRUB's theme folder (`/boot/grub/themes`), remember, paste the entire folder, not just the `theme.txt`
4. Open `/etc/default/grub`, find and modify these lines

        # Uncomment one of them for the gfx desired, a image background or a gfxtheme
        #GRUB_BACKGROUND="/path/to/wallpaper"
        GRUB_THEME="/boot/grub/themes/own-grub-theme/theme.txt"

5. Generate your GRUB config