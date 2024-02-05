# Flashing steps for my k4.19 roms

**NOTE:** You may face some errors as `Failed to mount system` just ignore it.

### Clean Flash if coming from normal partitions ROMs

1. Flash this [Recovery](https://sourceforge.net/projects/lc-dev/files/lavender/TWRP-recovery-erofs-dynamic-partitions-230713.img/download)
2. Reboot to the new recovery (if it didn't reboot itself).
3. Wipe system, vendor, metdata, cache.
4. Flash ROM
5. Format data
6. Reboot
7. Enjoy :)

### Clean Flash if coming from another retrofit partitions ROMs

1. Reboot to recovery
2. Format Data
3. Flash ROM.zip
4. Reboot
5. Enjoy :)

### Dirty Flash

1. Flash the rom
2. Wipe dalvik, cache
3. Reboot
4. Enjoy

### Kernel SU
> At your own risk!!
* flash [This boot.img](https://sourceforge.net/projects/evolution-x/files/lavender/14/boot.img/download)
