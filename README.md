# BerryConverter

Berryboot image conversion script

Prerequisite:

A regular Linux desktop computer that has **kpartx** and **mksquashfs** installed.

Setup

copy berryboot_conv.sh in a folder of your choice togheter with the Raspberry image file.
Change the script permission to executable with:

>`chmod 755 berryboot_conv.sh`

Usage:

>`./berryboot_conv.sh <name_image_to_convert> <name_converted_image>`

Example:

> `./berryboot_conv.sh raspios.img raspios_berry.img`
  
The converted image file can be copied to a USB stick and then choosen to be installed in berryboot.
The converted image can be used also in a local network repository.
