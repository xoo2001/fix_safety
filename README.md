Install Gsi Rom

Commands:
1. adb reboot bootloader
2. fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
3. fastboot --disable-verity --disable-verification flash vbmeta_system vbmeta_system.img
4. fastboot reboot fastboot
5. fastboot delete-logical-partition product
6. fastboot flash system system.img (must be arm64 A/B)
7. fastboot -w
8. fastboot reboot
