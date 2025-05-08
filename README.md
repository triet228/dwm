# dwm
Triet's version of suckless dwm. Basically dwm with some minor twist to fit Triet's customization. Keep the suckless philosophy in mind, so less patch is better and align as close to default as possible while making it usable.

Source code: https://dwm.suckless.org/

Note: dwm does not run on Wayland, it runs on X11 only.

## Download
```git clone https://github.com/triet228/dwm.git```
## Installtion
```cd dwm``` \
```sudo make clean install```
## Run dwm
First go to home directory \
```cd ~```\
Open .xinitrc or if doesn't exist, create file .xinitrc\
```touch .xinitrc```\
If you know how to use vim: ```vim .xinitrc```\
Add this line at the end of .xinitrc file\
```exec dwm```\
Log out of current GUI session\
Go to a tty session: Ctrl + Alt + F4\
Login with username and password\
Disable current desktop environement. Likely ```sudo systemctl disable <Desktop Environment Name>``` \
Reboot? Maybe\
Go to a tty session: Ctrl + Alt + F4\
Login with username and password\
Start X session\
```startx```\
Read error message. Likely there will be.\
Debug it. Good luck have fun haha\
Once it works, you should be launched into the typical dwm\
To toggle top bar\
Alt + B\
To open terminal\
Alt + Shift + Enter\
