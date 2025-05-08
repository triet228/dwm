# dwm
Note: dwm runs on Linux only. It's a dynamic window manager.

This is Triet's version of suckless dwm. Basically dwm with some minor twist to fit Triet's customization. Keep the suckless philosophy in mind, so less patch is better and align as close to default as possible while making it usable.

Source code: https://dwm.suckless.org/

## Current feature
1. No border. Default has 1 pixel border
2. No top bar. Default has top bar. Toggle it with Alt + B
3. st is tag 1
4. firefox is tag 2

## Download
```git clone https://github.com/triet228/dwm.git```
## Installtion
Go to cloned directory
```cd dwm``` 

Install
```sudo make clean install```


Uninstall
```sudo make uninstall```

## Run dwm

Note: dwm does not run on Wayland, it runs on X11 only. Check if you are using Wayland or X11 first. If you want to keep Wayland, just give up dwm and use alternative


First go to home directory ```cd ~```

Open .xinitrc or if doesn't exist, create file .xinitrc ```touch .xinitrc```

If you know how to use vim: ```vim .xinitrc```


Add this line at the end of .xinitrc file ```exec dwm```


Log out of current GUI session


Go to a tty session: Ctrl + Alt + F4


Login with username and password


Disable current desktop environement. Likely ```sudo systemctl disable <Desktop Environment Name>``` 


Reboot? Maybe


Go to a tty session: Ctrl + Alt + F4


Login with username and password


Start X session ```startx```


Read error message. Likely there will be.


Debug it. Good luck have fun haha


Once it works, you should be launched into the typical dwm


To toggle top bar: Alt + B


To open terminal: Alt + Shift + Enter
