# Leapmotion on Arch notes

```
$ git clone https://aur.archlinux.org/leap-motion.git; cd leapmotion; makepkg -sir
$ sudo usermod -a -G plugdev $USER
$ systemctl start leapd.service
$ LeapControlPanel
```


