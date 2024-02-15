Just a simple bash script wizard to install Arch Linux after you have booted on the official Arch Linux install media.

## How to use

First, boot with the [last Arch Linux image](https://www.archlinux.org/download/) with a [bootable device](https://wiki.archlinux.org/index.php/USB_flash_installation_media).

Then make sure you have Internet connection on the Arch iso. If you have a wireless connection the [`iwctl`](https://wiki.archlinux.org/index.php/Iwd#iwctl) command might be useful to you. 
You can also read the [Network configuration](https://wiki.archlinux.org/index.php/Network_configuration) from the Arch Linux guide for more detailed instructions.

Since I am making this script only for myself, it is located in the FTP folder on my home router.

You can download it with the following command

##curl -u user:password -O ftp://192.168.1.1/archinstall
