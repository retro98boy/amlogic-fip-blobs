```
dd if=mmcblk0boot0 of=fip bs=512 skip=1 conv=notrunc
gxlimg -e fip extract
```
