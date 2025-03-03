# This is how to use an external disk on linux
## First open your terminal
Ctrl + Alt + T

## Make directory on ur device

1. lsblk
2. sudo mkdir -p /media/usr/<!--Change usr to username-->
3. sudo mount -o loop /dev/sdbX /media/usr/Disk <!--Change X that indicates the disk-->

Now you can use the external disk.