# Dual Boot a fresh Ubuntu 16.04 on Windows 10 (64bit):
**Following steps are what I did for my Dual Boot system Asus GT703G Laptop**

Based on various blogs particularly this.[vip link to follow][1]

1) Downloaded Ubuntu i386 iso(for 32 bit) or amd64(for 64 bit) from [here][2]. 
    Need to use amd64 Ubuntu iso file rather than i386 iso. It works for Intel machine(verified by ask-ubuntu).
2) Created bootable USB using [this][3]
3) Made the partition of 300 GB in my D drive to install Ubuntu[1]
4) Disabled "fast boot" option
    Shift+Restart-> Troubleshoot-> Advanced Setting->UIFE Firmware setting->Restart->Advanced mode->boot
5) Disable Secure Boot option
    Shift+Restart-> Troubleshoot-> Advanced Setting->UIFE Firmware setting->Restart->Advanced mode->find somewhere here
6) Boot menu has 2 boot options. I have set higher priority to USB booting. As shown in the above screenshot.
7) Enabled USB Legacy Support
    Shift+Restart-> Troubleshoot-> Advanced Setting->UIFE Firmware setting->Restart->Advanced mode->find somewhere here
8) Save and Restart

For screenshots Please refer following questions:
Stachoverflow[4] superuser[5]

[1]: https://superuser.com/questions/1375497/dual-boot-issue-with-windows-10-and-ubuntu-16-on-asus-gt-703g-laptop
[2]: http://old-releases.ubuntu.com/releases/16.04.4/
[3]: https://itsfoss.com/create-live-usb-of-ubuntu-in-windows/
[4]: https://stackoverflow.com/questions/53308770/dual-boot-issue-with-windows-10-and-ubuntu-16-on-asus-gt-703g-laptop?noredirect=1#comment93498344_53308770
[5]: https://superuser.com/questions/1375497/dual-boot-issue-with-windows-10-and-ubuntu-16-on-asus-gt-703g-laptop
