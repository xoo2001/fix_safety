Install stockrom infinix

Commands:
1.  adb reboot bootloader
2.  fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
3.  fastboot --disable-verity --disable-verification flash vbmeta_system vbmeta_system.img
4.  fastboot reboot fastboot                     
5.  fastboot delete-logical-partition product
6.  fastboot reboot bootloader
7.  fastboot flash super super.img
8.  fastboot reboot fastboot
9.  fastboot -w
10. fastboot reboot
