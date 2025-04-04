# KlipperScreen for Fiber Laser Galvo Unit

NOT FOR 3D PRINTERS USE - Under construction

- Follow normal Klipper installation with KIAUH
    https://github.com/dw-0/kiauh

Install Klipper, Moonraker, Fluidd, KlipperScreen

- For Android Smartphone use as a screen, follow this procedure for Xserver-XSDL installation
   https://klipperscreen.readthedocs.io/en/latest/Android/

- Once you have default install, extract CONFIG_FILES.zip on your computer

  https://github.com/RemyBaligant/KlipperScreen_FiberGalvo/blob/master/CONFIG_FILES.zip

In zip file, each sub folder contains files to be overwritted on your pi

You can use program like WINSCP for people not famliliar with command line

home_pi_KlipperScreen_config , copy move_menu.conf in /home/pi/KlipperScreen/config/

home_pi_KlipperScreen_panels , copy main_menu.py in /home/pi/KlipperScreen/panels/

home_pi_printer_data_config, copy files in /home/pi/printer_data/config/


- Printer.cfg

The printer.cfg in zip file is an example. It use FLYF407ZG board but you can edit the file to use another board. This files contains menu macros for FocusGalvo.
You have to enter your own focus distance and defocus memory for each lens used. 
Follow "#" in file for more information

- Klipperscreen.conf

This file contain menu layout, Follow "#" in file for more information

---------------------------------------------

KlipperScreen is a touchscreen GUI that interfaces with [Klipper](https://github.com/Klipper3d/klipper) via [Moonraker](https://github.com/arksine/moonraker). It allows you to switch between multiple printers and access them from a single location. Notably, it doesn't need to run on the same host as your printer; you can install it on another device and configure the IP address to connect to the printer.

### Documentation

For detailed information, [click here to access the documentation](https://klipperscreen.github.io/KlipperScreen/).

### Inspiration

KlipperScreen draws inspiration from [OctoScreen](https://github.com/Z-Bolt/OctoScreen/) and was developed to provide a native touchscreen GUI compatible with [Klipper](https://github.com/Klipper3d/klipper) and [Moonraker](https://github.com/arksine/moonraker).

[![Main Menu](docs/img/panels/main_panel.png)](https://klipperscreen.readthedocs.io/en/latest/Panels/)

Explore more screenshots [here](https://klipperscreen.readthedocs.io/en/latest/Panels/).

### Translations

Translations for KlipperScreen are hosted on Weblate. Thanks to the Weblate team for supporting the open-source community.

<a href="https://hosted.weblate.org/engage/klipperscreen/">
    <img src="https://hosted.weblate.org/widget/klipperscreen/svg-badge.svg" alt="Translation status" />
</a>

Click the widget below to access the translation platform:

<a href="https://hosted.weblate.org/engage/klipperscreen/">
    <img src="https://hosted.weblate.org/widget/klipperscreen/horizontal-auto.svg" alt="Weblate widget" width="50%" />
</a>

### About the Project

KlipperScreen was created by Jordan Ruthe in 2020.

| Donate to Jordan |
|------------------|
| [Patreon](https://www.patreon.com/klipperscreen) |
| [Ko-fi](https://ko-fi.com/klipperscreen) |

Since 2021, the project has been maintained by Alfredo Monclus (alfrix).

| Donate to Alfrix |
|------------------|
| [Ko-fi](https://ko-fi.com/alfrix) |

We extend our gratitude to all contributors who have helped along the way. [Meet the contributors](https://github.com/KlipperScreen/KlipperScreen/graphs/contributors).

### Sponsors

![LDO](docs/img/sponsors/LDO.png) ![YUMI](docs/img/sponsors/YUMI.png)

Special thanks to [LDO](https://ldomotors.com/) and [YUMI](https://wiki.yumi-lab.com/) for sponsoring KlipperScreen and the open-source community.
