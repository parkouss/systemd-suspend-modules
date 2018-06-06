# Reload modules on suspend / hibernate

# Installation

If you use arch-based distro, install it via AUR. For yaourt : 

`yaourt -S systemd-suspend-modules`

Alternatively, you can clone this repo, navigate to repo location and execute `makepkg -si` to build the pkg. Then, launch `sudo pacman -U systemd-suspend-modules` to install it via pacman, or with `makepkg --install`.

Unfortunately, there is no out-of-the-box installation for other Linux based distros. Stay tuned for more support.

# Usage 

After installing, open `/etc/suspend-modules.conf` with your favorite text editor. Add your troublesome kernel modules there, line by line. For more information about kernel modules, visit [related archwiki.](https://wiki.archlinux.org/index.php/Kernel_module)