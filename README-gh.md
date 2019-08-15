
```
make
make tcz
cp tce-extension/gh-ardui-pi-oled.tcz /mnt/mmcblk0p2/tce/optional
# if it's not already there, add gh-ardui-pi-oled.tcz to 
# /mnt/mmcblk0p2/tce/onboot.lst, e.g.
# echo gh-ardui-pi-oled.tcz >>  /mnt/mmcblk0p2/tce/onboot.lst
