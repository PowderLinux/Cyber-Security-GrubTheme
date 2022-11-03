# Cyber-Security-GrubTheme
Cyber-Security theme for Grub2 bootloader

____________________________________________________________________________

Cyber Security theme for Grub2.


Supported languages: English, French, German, Norwegian, Portuguese, Russian, Ukrainian, Chinese (simplified).


NOTICE: This theme looks best on lower resolution screens.
(Best results 1280x1024) (Created on a QEMU-KVM VM with a 1280x1024 display)
I am currently working on another version for higher resolution screens..

____________________________________________________________________________

Install:

Copy the folder 'Cyber-Security' to /boot/grub/themes >
(use 'sudo mkdir /boot/grub/themes' if you dont have a 'themes' folder)

Add the following line to /etc/default/grub >
(use 'sudo gedit /etc/default/grub')
GRUB_THEME="/boot/grub/themes/Cyber-Security/theme.txt"

Update your grub.cfg >
(use 'sudo update-grub', or 'sudo grub2-mkconfig -o /boot/grub/grug.cfg)

If you did everything rite, you will see:
Generating grub configuration file ...
Found theme: /boot/grub/themes/Cyber-Security/theme.txt

Done!

____________________________________________________________________________

Created by p0wder (https://github.com/PowderLinux)


Credits:

Andrei Shevchuk (https://github.com/shvchk)
Multi-Language support from Shvchk's 'Poly-Light' grub theme.
(MIT License)

Llewelyn Trahaearn (https://www.opendesktop.org/member/461881)
I used the icons from his 'Standby' grub theme in this theme.

____________________________________________________________________________
