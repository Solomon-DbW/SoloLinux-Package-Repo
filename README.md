# SoloLinux-Package-Repo

## Install SoloLinux GUI config

### Via pacman
Append this to the end of /etc/pacman.conf file:   \n
`[sololinux-hyprland]
SigLevel = Optional TrustAll
Server = https://solomon-dbw.github.io/SoloLinux-Package-Repo/x86_64`

Run `sudo pacman -Sy` to update pacman database.
Run `sudo pacman -S sololinux-hyprland` to install package

### Via tarball
[Get tarball here](https://github.com/Solomon-DbW/SoloLinux-Package-Repo/blob/main/x86_64/sololinux-hyprland-1.0.0-1-any.pkg.tar.zst)

Run this in the tarball install directory:   \n
`sudo pacman -U sololinux-hyprland-1.0.0-1-any.pkg.tar.zst`

