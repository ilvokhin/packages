Confuguration files for Arch Linux packages.


HOWTO

$ mkdir ~/chroot
$ CHROOT=$HOME/chroot
$ mkarchroot $CHROOT/root base-devel
$ arch-nspawn $CHROOT/root pacman -Syu
$ cd package
$ makechrootpkg -c -r $CHROOT


REFERENCES

[1]: https://wiki.archlinux.org/title/DeveloperWiki:Building_in_a_clean_chroot
