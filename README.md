Bing Wallpaper for Ubuntu
=================================

Information
-----------
A script which downloads the latest picture of the day from Bing.com and saves
it to a directory.

The script was tested on:
    Ubuntu 12.04 - 15.04


How to use?
-----------
* Just run the **bing-wallpaper.sh** script from the terminal. The script will
download the bing image.
* If desired, change the default **PICTURE_DIR** in **bing-wallpaper.sh** to the
wallpaper directory. If left unchanged the default value is
**~/Pictures/bing-wallpapers/**.

Configuration on Ubuntu
-----------------------
**TL;DR:**

* To install Gnome background slideshow, in the terminal run:

```
$ git clone https://github.com/arashsoft/bing-wallpaper.git
$ bing-wallpaper/Tools/gnome-bing-slideshow/deploy-gnome-settings.sh
```

* Register `bing-wallpaper/Tools/startup.sh` to run regularly.

* Change the background properties to use the new slideshow.

**How to register bing-wallpaper.sh or bing-random-pic.sh to run regularly.**

There are two ways to run the scipts regularly: cron jobs and startup
applications.
* Cron jobs:
  * Change the path of **bing-wallpaper.sh** in **Tools/bing-cron** to the
    desired script location. If left unchanged the default value is
    **~/Pictures/bing-wallpaper.sh**.
  * From the terminal run `crontab /path/to/bing-cron` to setup the cronjob.
* Startup programs:
  * From HUD, search for startup applications.
  * Add **bing-random-pic.sh** or **bing-wallpaper.sh**.

The Ubuntu script was tested in Ubuntu 12.04 - 13.10.

Acknowledgement
---------------
Original script by ktmud can be found at
[https://github.com/ktmud/bing-wallpaper](
https://github.com/ktmud/bing-wallpaper).


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/thejandroman/bing-wallpaper/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

