# yum-repo-mooz

A yum repo maintained by [@moozhub](https://github.com/moozhub)

### Overview

My (sometimes pathetic) attempts at building RPM packages for programs I need. Hopefully they are of use to others.

### Repository highlights

* [kodi:krypton](https://github.com/xbmc/xbmc/tree/Krypton) - Kodi Home Theater Software
* [rtorrent:master](https://github.com/rakshasa/rtorrent) - rTorrent BitTorrent client
* [kmod-megaraid_sas-07.702.06.00](https://hwraid.le-vert.net/wiki/LSIMegaRAIDSAS#a2.Linuxkerneldrivers) - Latest LSI megaraid_sas kernel module
* [megacli-8.07.14](https://hwraid.le-vert.net/wiki/LSIMegaRAIDSAS#a3.3.megacli) - Latest LSI megacli utility
* [storcli-1.23.02](https://www.thomas-krenn.com/en/wiki/StorCLI) - Latest LSI storcli utility
* [openrazer:stable](https://github.com/openrazer/openrazer) - A collection of Linux drivers for Razer devices
* [polychromatic:stable](https://github.com/lah7/polychromatic) - Graphical front end and tray applet for configuring Razer peripherals on GNU/Linux

### Installing

CentOS 7 / EL7

```
sudo yum-config-manager --add-repo=https://raw.githubusercontent.com/moozhub/yum-repo-mooz/master/elmooz.repo
```

### Install packages

```
sudo yum clean all
sudo yum install kodi
```
