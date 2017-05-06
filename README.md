# hacks
nice idea
+ diskutil list
+ hdiutil convert /Users/ling/Downloads/DEEP_GHOST_XP_SP3_V2017_04.iso -format UDRW -o /Users/ling/Downloads/DEEP_GHOST_XP_SP3_V2017_04.img
+ diskutil unmoutDisk /dev/disk2
+ sudo dd if=/Users/ling/Downloads/DEEP_GHOST_XP_SP3_V2017_04.img.dmg of=/dev/disk2 bs=10m
