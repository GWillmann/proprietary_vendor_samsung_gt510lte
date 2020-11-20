# How these files were extracted

I issued the following commands:

```
adb shell
tar -czvf /sdcard/vendor.tar.gz /system/vendor/
adb pull /sdcard/vendor.tar.gz $HOME/Downloads/gt510lte
```
