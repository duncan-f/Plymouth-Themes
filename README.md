 # Bsol (Blue Screen Of Life)
![plymouth ](https://github.com/user-attachments/assets/ea6b1579-eda4-435b-bb8f-47868fdfc21e)

# Jam (Just A Moment)
![jam](https://github.com/user-attachments/assets/21d0d9a7-770b-44e6-83ca-0ae6a88477d0)

# Installation
- Install plymouth on your distro by following guide written on your distro's wiki page or search on the internet. Do follow each and every steps properly.
  
  [Arch](https://wiki.archlinux.org/title/Plymouth)  [Debian](https://wiki.debian.org/plymouth)  [Ubuntu](https://wiki.ubuntu.com/Plymouth) [Linux-Mint](https://community.linuxmint.com/tutorial/view/646)  [Nix-OS](https://wiki.nixos.org/w/index.php?title=Plymouth&mobileaction=toggle_view_desktop)  [Gentoo](https://wiki.gentoo.org/wiki/Plymouth)  [EndeavourOS](https://forum.endeavouros.com/t/guide-how-to-install-and-use-plymouth/51363)  [Fedora](https://discussion.fedoraproject.org/t/enable-plymouth-startup/70079)  [MX-Linux](https://mxlinux.org/wiki/system/add-plymouth-to-mx-linux/)  [Manjaro](https://wiki.manjaro.org/index.php/Plymouth)  [oepnSUSE](https://en.opensuse.org/openSUSE:Plymouth)   

- Once you installed plymouth make sure that you have a themes folder inside /usr/share/plymouth/ if not then create one
```
sudo mkdir /usr/share/plymouth/themes/
```

- Clone this repository 
```
git clone https://github.com/MrVivekRajan/Plymouth-Themes.git
```

- After cloing it just copy and paste your desired Plymouth Theme to `/usr/share/plymouth/themes/`

- Now just set it as default Plymouth theme and make sure to rebuild `initrd` for that just use commands given below:-

- For Bsol-Theme 
```
sudo plymouth-set-default-theme Bsol -R 
```
- For Jam-Theme 
```
sudo plymouth-set-default-theme Jam -R 
```

# Also Available at:-
- [Pling](https://www.pling.com/p/2216301/)

- [Gnome-Look](https://www.gnome-look.org/p/2216301)

# Credits  
- [K Harishnkr](https://github.com/harishnkr) for Blue Screen of Life Idea
- [Mauro Meloni](https://gitlab.com/maurom) for circular loading animation
