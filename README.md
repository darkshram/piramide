# Plymouth Piramide Theme.
Plymouth theme with a photo of a Palanque Piramid.

Photo the main piramid of Palenque, Mexico, by Peter Vandecaveye, available is under Public Domain and was taken from

https://pixabay.com/es/mexico-ruina-maya-cultura-853048/

# Installation.

This theme requires plymouth-plugin-script.

```
pkcon install plymouth-plugin-script

git clone https://github.com/darkshram/piramide/

sudo cp -a piramide /usr/share/plymouth/themes/

plymouth-set-default-theme piramide

dracut -f

reboot
```
