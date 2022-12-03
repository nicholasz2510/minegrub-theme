# minegrub-theme
A Grub Theme in the style of Minecraft!

When you have more/less than 4 boot options, you might want to adjust the height of the bottom bar (that says "Options" and "Console")
The formula is in the theme.txt, so you should be able to easily adjust it.

### How do i install it??
- just `git clone` it into your `/boot/grub/themes/` folder
- change/add this line in your `/etc/defaults/grub`:
```
GRUB_THEME=/boot/grub/themes/minegrub-theme
```
- update your live grub config by running `sudo grub-mkconfig -o /boot/grub/grub.cfg`
- your good to go

### Notes:
- the `GRUB_TIMEOUT_STYLE` in the defaults/grub file should be set to `menu` so it immediately shows the menu (else you would need to press ESC)
- im no linux expert, thats why i explain it so thoroughly, for other newbies :>
- i use arch btw
- screenshot coming soon


Font downloaded from https://www.fontspace.com/minecraft-font-f28180 and used for non commercial use.