TGA - Tweaked Gnome's Adwaita
=============================

This theme is supposed to provide a cleaner experience being as closest as
possible to Adwaita, so future changes can be merged easily.

I based most of this theme in the color scheme of:

https://github.com/Elbullazul/OS-X-El-Capitan

Screenshots
-----------

![Screenshot 01](https://raw.githubusercontent.com/ronisbr/TGA/master/screenshots/screenshot_01.png)

![Screenshot 02](https://raw.githubusercontent.com/ronisbr/TGA/master/screenshots/screenshot_02.png)

![Screenshot 03](https://raw.githubusercontent.com/ronisbr/TGA/master/screenshots/screenshot_03.png)

Installation
------------

You only need to clone the repository inside your `themes` folder:

```
cd ~
mkdir -p .themes
cd themes
git clone https://github.com/ronisbr/TGA.git
```

Then select **TGA** theme for GTK and Gnome shell in `gnome-tweak-tool`.

If you want to change the buttons position to match what you see in the
screenshots, execute:

```
gsettings set org.gnome.desktop.wm.preferences button-layout 'close,minimize,maximize:'
```

**NOTE**: You must have the **User Theme** extension to change the Gnome shell
theme. It can be installed from:

https://extensions.gnome.org/extension/19/user-themes/

Overview Wallpaper
------------------

The overview wallpaper will be the one in `./TGA/wallpapers/wallpaper-blur.jpg`
regardless the selection in the desktop. Hence, after you decide what wallpaper
you will use, create a blurred, darker version and overwrite the
`wallpaper-blur.jpg` file.

Additional Information
----------------------

* The gnome shell theme was forked from:

https://github.com/GNOME/gnome-shell/tree/master/data/theme

* The **GTK 3.0** theme was forked from:

https://github.com/GNOME/gtk/tree/master/gtk/theme/Adwaita

* The **GTK 2.0** theme was forked from:

https://github.com/GNOME/gnome-themes-standard

* The default wallpaper was obtained from:

https://alpha.wallhaven.cc/wallpaper/373848
