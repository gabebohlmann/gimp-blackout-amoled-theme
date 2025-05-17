### Guide For Linux Flatpak App
  1. Create a new folder in the GIMP `/themes` directory.
      * In terminal `cd "/var/lib/flatpak/app/org.gimp.GIMP/x86_64/stable/{uniqueFlatPakID}/files/share/gimp/3.0/themes/"`
      * `sudo mkdir BlackoutAmoled`
      * `sudo cd BlackoutAmoled`
  2. Create a `gimp-dark.css` file with `sudo touch gimp-dark.css` in `.../BlackoutAmoled$` terminal,                
  3. Open `gimp-dark.css` and copy the contents from this repo into the file and save. The text editor Kate allows for saving with `sudo`.
  4. Open GIMP and change to the new theme in `Toolbar > Edit > Preferences > Themes`.

#### Notes
  * This theme does not have any color scheme variants besides `gimp-dark`. Changing the color scheme variant in the theme selector dropdown menu will have no effect.
  * This theme has not been extensively tested so there could be visibility problems and various strange behavior. Most components have been set to have a background of `#000000`.
  * Feel free to submit a PR for any issues or improvents.

#### TODO
  1. IMPORTANT: Makes theme borderline unusable. Tooltip hover on tools in left sidebar disappear. 
  1. The File, Edit, etc. Menubar turns grey when the window loses focus. Figure out how to keep it `#000000` on focus loss.
  1. Update selection color. Currently it is bright blue.
  1. Fix problem with text in Menubar dropdowns having a different highlight background color than the Menubar itself.
  1. Add guides for the Linux App Image and Windows App with the correct `/themes` directory location.

    
