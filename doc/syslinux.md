= Install Syslinux 6.03 =

To install SYSLINUX in MikeOS type:

```
make bios efi64 installer
install -m 755 bios/extlinux/extlinux /MikeOS/bin
install -m 755 bios/linux/syslinux /MikeOS/bin
mkdir -pv /MikeOS/lib/syslinux/modules/{bios,efi64}
mkdir -pv /MikeOS/lib/syslinux/efi64/
find ./bios/com32/ -name *.c32 -exec cp {} /MikeOS/lib/syslinux/modules/bios/ \;
find ./efi64/com32/ -name *.c32 -exec cp {} /MikeOS/lib/syslinux/modules/efi64/ \;
cp efi64/efi/syslinux.efi /MikeOS/lib/syslinux/efi64/
```