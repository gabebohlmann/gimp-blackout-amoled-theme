# Tutorial

## For Linux Flatpak App
  1. Create a new BlackoutAmoled folder in the GIMP themes directory.
      * This is found at `/var/lib/flatpak/app/org.gimp.GIMP/x86_64/stable/{uniqueFlatPakID}/files/share/gimp/3.0/themes/`
  2. Create a `gimp-dark.css` file with `$sudo touch gimp-dark.css`
  3. Open `gimp-dark.css` and copy the contents from this repo into the file and save
  4. Open GIMP and change to the new theme in `Toolbar > Edit > Preferences > Themes`

#### Notes
  * This theme does not have any color scheme variants besides `gimp-dark`, changing the color scheme variant in the theme selector dropdown menu will have no effect.
  * This theme has not been extensively tested so there could be visibility problems and various strange behavior. Most components have been set to have a background of `#000000`
  * Feel free to submit a PR for any issues or improvents.

#### Known Issues
  1. The File, Edit, etc. Menubar turns grey when the window loses focus. 
    