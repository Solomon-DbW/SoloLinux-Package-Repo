# SoloLinux-Package-Repo

## Install SoloLinux GUI Config

### Via pacman

Append this to the end of your `/etc/pacman.conf` file:

```
[sololinux-hyprland]
SigLevel = Optional TrustAll
Server = https://solomon-dbw.github.io/SoloLinux-Package-Repo/x86_64
```

Update your pacman database:

```bash
sudo pacman -Sy
```

Install the package:

```bash
sudo pacman -S sololinux-hyprland
```

---

### Via tarball

Download the tarball:

[sololinux-hyprland-1.0.0-1-any.pkg.tar.zst](https://github.com/Solomon-DbW/SoloLinux-Package-Repo/blob/main/x86_64/sololinux-hyprland-1.0.0-1-any.pkg.tar.zst)

Install it manually:

```bash
sudo pacman -U sololinux-hyprland-1.0.0-1-any.pkg.tar.zst
```

---

