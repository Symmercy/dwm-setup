# dwm-setup

DONT RUN THIS AS ROOT!
This is my script that sets up dwm to my liking (on arch)

After you run this script, and go into dwm, you should open lxappearance and change the icon theme to papirus, gtk theme to dracula
and the cursor theme to layan

Add any lines you want to the .xprofile file, I added feh picom slstatus and polkit-gnome as a baseline,

the most important keybindings are 
meta_p == dmenu
meta_shift_c == close program

for the rest you can check out the config

![Screenshot_archlinux_2023-05-07_12:13:36](https://user-images.githubusercontent.com/91673840/236671541-8830e1c5-20e9-4666-bc1f-cca950f13ade.png)
old config
there are small differences (I didn't update the screenshot)
![image](https://github.com/Symmercy/dwm-setup/assets/91673840/fdf08740-88be-40b5-81c3-6ae5c08af730)
old config
![2023-08-10_12-16](https://github.com/Symmercy/dwm-setup/assets/91673840/25a3dc2e-4df6-4014-afe9-b9c723e24416)
new config


i get all of my wallpapers from this repo https://github.com/Gingeh/wallpapers

if lightdm breaks, just enable ly with sudo systemctl enable ly && sudo systemctl disable lightdm

