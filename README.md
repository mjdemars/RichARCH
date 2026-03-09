# RichARCH
Your concierge creating a Rich experience to Arch

RichARCH is designed to be a Quick Simpler Path to Arch with automation and ricing options.

* Just one command to start the latest complete installer for Arch.

One goal is to only use packages in the basic Arch Linux repos by default with the option to install some non-standard packages. Our hope is that this will help to make Arch Linux more approachable to individual and corporate users.

GUIs: Budgie/Cinnamon/Cosmic/Cutefish/Enlightenment/Gnome/Hyprland/KDE/LXDE/LXQT/Mate/Niri/River/Sway/XFCE

Kernels: linux/linux-cachyos/linux-hardened/linux-lqx/linux-lts/linux-nitrous/linux-tachyon/linux-zen/linux-znver2/linux-znver3/linux-znver4/linux-znver5

Profiles: SecOps/Server/Omarchy/HyprVibe/KoolsDots/SaatvikDots/ShellNinja/TheBlackDon/VaelixdDots

https://sourceforge.net/projects/richarch/

### Details and installation info can be found at:
https://download.sourceforge.net/richarch/InstallAndInfo.pdf

https://sites.google.com/view/richarch

### Supports:
* Simple helpful menu structure
* Software from multiple stable repos
* Fully automated installs avaliable
* Multiple install profiles avaliable
* Orchestration compatible
* Pure Arch to complete ricing options
* AMD/Nvidia/Nvidia-Old drivers
* BTRFS/EXT4/XFS/LVM options
* Kickstart like features available

++++++++++++++++++++++++++++++++++++++++++

INSTALL (to start the RichARCH Arch installer)

After booting from the Arch ISO, to run the RichARCH installer type:

bash <(curl -L download.sourceforge.net/richarch/install)

    Added option to install additional alternative kernels (like: linux-cachyos, linux-lqx, linux-zen, ...).

    Repaired launcher for Omarchy.

    Repaired var partitioning for server installs.

    Simplified menus and added progression bars.

    Added Hyprland ricing options: Jupiter Broadcasting's HyprVibe, Kool's Hyprland Dots, and Shell Ninja's Dots

    Added Niri ricing options: DonArch Dots, Saatvik Dots, and Vaelixd Dots

    Added option to setup a custom Omarchy base install and start the online Omarchy installer.

    With the issues that GRUB caused on Arch in 2022, systemd-boot is now used on systems using UEFI.

++++++++++++++++++++++++++++++++++++++++++

HELP (print quick help info)

After booting from the Arch ISO, to print quick help type:

bash <(curl -L download.sourceforge.net/richarch/help)

++++++++++++++++++++++++++++++++++++++++++

MAKEFLAGS (for creating your own flagoptions file)

After booting from the Arch ISO, to create flagoptions file type:

bash <(curl -L download.sourceforge.net/richarch/makeflags)

++++++++++++++++++++++++++++++++++++++++++

UI (for adding a desktop environment to an already installed Arch system)

From an installed Arch system, to run the GUI installer type:

bash <(curl -L download.sourceforge.net/richarch/ui)

    Fixed syntax crash error.

    Simplified menus and added progression bars.

    Added Hyprland ricing options: Jupiter Broadcasting's HyprVibe, Kool's Hyprland Dots, and Shell Ninja's Dots

    Added Niri ricing options: DonArch Dots, Saatvik Dots, and Vaelixd Dots

++++++++++++++++++++++++++++++++++++++++++

EXTRASFTW (for adding extra software to an already installed Arch system)

From an installed Arch system, to run the extra software installer type:

bash <(curl -L download.sourceforge.net/richarch/extrasftw)

    Apps available: ani-cli ardour audacity betterbird-bin blender bottles cartridges calligra-plan codeblocks darktable devhelp digikam discord dms-shell-git falkon fish floorp freecad freerdp geany gedit gimp gnome-boxes google-chrome gpodder gradia handbrake heroic-games-launcher-bin inkscape intellij-idea-community-edition jellyfin-desktop jellyfin-server kando-git kasts kdenlive keepassxc kicad krita kdiagram leafpad librecad libreoffice librewolf liteide l3afpad looking-glass-git lutris mypaint mousepad noctalia-shell notepadnext obs-studio-stable octopi oh-my-posh-bin onlyoffice-bin open-vm-tools openscad pamac paru piper podman-ui pycharm-community-edition qcad quickemu-gui rapidraw retroarch retroarch-assets-ozone scribus shotcut shotwell signal-desktop slack-desktop spotify steamcmd telegram-desktop terminator tigervnc tmux ulauncher visual-studio-code-bin virtmanager virtualbox virtualbox-guest-utils vivaldi vmware-workstation wireshark wps-office yabridge yt-dlp zen-browser-bin zellij zfs zsh warpterm

++++++++++++++++++++++++++++++++++++++++++

BETA:

HYPRVIBE (for adding the HyprVibe ricings with Noctalia shell to a user on an already installed Arch system with Hyprland)

From an installed Arch system with Hyprland already installed, to run the HyprVibe installer type:

bash <(curl -L download.sourceforge.net/richarch/hyprvibe)

+++++++

LIBALPM-FRAMEPATCH (for patching the libalpm15 library used pamac and other apps and the libsframe library used by Looking Glass)

From an installed Arch system, to run the libalpm-frame patch type:

bash <(curl -L download.sourceforge.net/richarch/libalpm-framepatch)

+++++++

MIRRORS (for updating an Arch system's mirrors list and repo keyring)

From an installed Arch system, to run the mirrors/keyring refresh type:

bash <(curl -L download.sourceforge.net/richarch/mirrors)

+++++++

SECOPS (for adding BlackArch security tools to an already installed Arch system)

From an installed Arch system, to run the SecOps installer type:

bash <(curl -L download.sourceforge.net/richarch/secops)

Source: README.md, updated 2026-03-09
