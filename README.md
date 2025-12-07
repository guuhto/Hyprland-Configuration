# Hyprland-Configuration
A clean and optimized Hyprland setup focused on simplicity, smooth visuals, and productivity. What follows is not a tutorial, but merely a guide for me.

**All configuration was done on Arch, btw.**

# Initial installation of Hyprland

**Installation**
```bash
sudo pacman -S hyprland waybar wofi
```
# CAVA
No modifications, no plugins, just CAVA.

# Fastfeth
Use the version above of: fastfetch 2.55.1-23-debug (x86_64)

**Installation(Arch)**
Install the -git version (or the latest available version) via AUR:
```bash
yay -S fastfetch-git
```
# GTK Themes and Fonts I use:

**Installation**

**Theme Nordic**
```bash
git clone https://github.com/EliverLara/Nordic.git
mkdir -p ~/.themes
cp -r Nordic ~/.themes/
```
**Icons Nordzy**
```bash
git clone https://github.com/MolassesLover/Nordzy-icon.git
cd Nordzy-icon
./install.sh
```
**Cursors Nordzy**
```bash
git clone https://github.com/guillaumeboehm/Nordzy-cursors.git
cd Nordzy-cursors
./install.sh
```
**Fonts**
```bash
sudo pacman -S ttf-firacode-nerd breeze breeze5 breeze-gtk papirus-icon-theme
```
# NWG Look

**Installation**
```bash
sudo pacman -S nwg-look
```
# QT5 and QT6

**Installation**
```bash
yay -S qt5ct-kde qt6ct-kde
```
# Dolphin corrections

**Installation**
```bash
sudo pacman -S archlinux-xdg-menu
```
**After**
```bash
XDG_MENU_PREFIX=arch- kbuildsycoca6
```
# Grim and Slurp(Print Screen)

**Installation**
```bash
sudo pacman -S grim slurp
```
# SDDM
```bash
https://github.com/JaKooLit/simple-sddm-2
```
