# L4T-Debian-12

This is a fork of Debian Bookworm that is capable of running on Nintendo Switch. Since it well known that the OS options on Nintendo Switch are very limited, we have decided to build an up to date OS for use on your Switch.

Wiki is currently being made https://github.com/zqpvr/L4T-Debian-12/wiki
If you want to contribute changes to the wiki that would be helpful!

Install goes like this
1. Download debian.tar.gz
2. Use this command while in L4T Ubuntu and in the directory that you installed debian.tar.gz to then you can `sudo mkdir /debian` `sudo mv debian.tar.gz /debian` `sudo tar xvpf debian.tar.gz -C /debian`
3. Then make a new partition using gparted called SWR-DEB and make sure it has allocated atleast 16GB
