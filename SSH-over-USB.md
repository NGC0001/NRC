# SSH over USB

## [Configuration](https://artivis.github.io/post/2020/pi-zero/)

After install raspian, before first boot:
  1. create empty file `/ssh`;
  2. append line `dtoverlay=dwc2` to `/boot/config.txt`;
  3. in `/boot/cmdline.txt`, append text ` modules-load=dwc2,g_ether` right after `rootwait`.

## Default account

* `ssh pi@raspberrypi.local`
* password: raspberry
