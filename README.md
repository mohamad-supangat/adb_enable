# Magisk Module for enable adb permanently

I use this script for my android which doesn't have a screen, and so that I always get adb access for remote scrcpy



feature:
enable Adb by default by setting build.prop




```
persist.adb.notify=0
persist.sys.usb.config=mtp,adb
ro.secure=0
ro.adb.secure=0
ro.debuggable=1
service.adb.root=1
persist.sys.root_access=1
persist.service.adb.enable=1
service.adb.tcp.port=7777
```
you can edit file system.prop to update values
