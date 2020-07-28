# KDE ISO ACTIONS
### Context menu actions for ISO files

## Installation:
1. copy **bin** folder to home directory
2. copy **ServiceMenus** to /home/YOURUSERNAME/.local/share/kservices5
3. add bin folder to PATH or if you have .local/bin in PATH already then copy it there instead

## Mount or Unmount from KDE file manager
you must have pkexec installed on your system

- right click any .iso file then **Actions for ISO** -> **Mount ISO** to mount. Enter password to continue.

- right click any .iso file then **Actions for ISO** -> **Unmount ISO** to unmount. Enter password to continue

mount location is /mnt/iso/**name-of-iso-file**

## Mount or Unmount using terminal
- mount: **sudo isomount name-of-iso-file.iso**
- unmount: **sudo isounmount name-of-iso-file.iso**
