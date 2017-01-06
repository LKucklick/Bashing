# Bashing
Some Bash stuff

how to clone a sd card

1)diskutil list

2)diskutil unmountDisk /dev/disk2 (and diskutil unmountDisk /dev/disk1)

3)sudo newfs_msdos -F 16 /dev/disk2

4)sudo dd if=/dev/disk1 of=/dev/disk2

5)to see the progress: insert ctrl + t
