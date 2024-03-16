## Nanachi Theme
This is a grub theme with nanachi

Forgive me that i can't provide real screenshots, but it should be run like this

![background.png](https://github.com/inuyasha-660/grub_theme_nanachi/blob/main/background.png)

## How to install

1. Git clone the repo to ``/boot/grub/themes/``

``````bash
git clone https://github.com/inuyasha-660/grub_theme_nanachi.git /boot/grub/themes/
``````

2. Then edit the ``/etc/default/grub``, find the ``#GRUB_THEME=``, delete the comment, and add the path to ``theme.txt``. 

Like this.
``````grub
GRUB_THEME="/boot/grub/themes/grub_theme_nanachi/theme.txt"
``````

3. Use ``grub-mkconfig -o /boot/grub/grub.cfg`` to update the Grub

4. Reboot, and enjoy it
