# Quick Guide for package building

    * Obtain existing package:
        * AUR: https://aur.archlinux.org/ (right box of package 'Download tarball'
        * Arch: ??
    * edit `PKGBUILD` and/or `MYPACKAGE.install` files
    * build package `makepkg -s`
    * install package `sudo pacman -U MYPACKAGE-x86_64.pkg.tar.gz`
    * ignore package: edit `/etc/pacman.conf` and add MYPACKAGE to 'IgnorePkg' config
    * remove `pkg` and `src` dirs
    * execute `git add .` to add files to git
    * commit this
