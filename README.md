# Lucidlinux Install

Install and configure archlinux has never been easier!

You can try it first with a `virtualbox`

## Prerequisites

- A fresh ArchLinux installation
- A working internet connection
- Logged in as 'root'

## How to get it with git
- Increase cowspace partition: `mount -o remount,size=2G /run/archiso/cowspace`
- Get list of packages and install git: `pacman -Sy git`
- get the script: `git clone git://github.com/xbc4000/lucidlinux`

## How to use
- Base-Script-1 [base]: `cd <dir> && ./base-script-1`
- Customise-Script-2 [customise]: `cd <dir> && ./customise-script-2`

## Dont want to select everything, rather just have a killer customised desktop?
- Auto-customise-3.automode [auto-customise]: `cd <dir> && ./auto-customise-3.automode`

## Base Script 1
- Configure keymap
- Select editor
- Automatic configure mirrorlist
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password

## Customise Script 2
- Backup all modified files
- Install additional repositories
- Create and configure new user
- Install and configure sudo
- Automatic enable services in systemd
- Install an AUR Helper [trizen, yay]
- Install base system
- Install systemd
- Install Preload
- Install Zram
- Install Xorg
- Install GPU Drivers
- Install CUPS
- Install Additional wireless/bluetooth firmwares
- Ensuring access to GIT through a firewall
- Install DE or WM [Cinnamon, Enlightenment, FluxBox, GNOME, i3, KDE, LXDE, OpenBox, XFCE]
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Games [Desura, PlayOnLinux, Steam, Minecraft...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure Web Servers
- Many More...
