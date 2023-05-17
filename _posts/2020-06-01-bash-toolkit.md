---
layout:     post
title:      Ubuntu Toolkit/ Command
subtitle:    "\"Useful command for ubuntu\""
date:       2023-05-17
author:     Baoyufuyou
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - ubuntu_setup
    - nvidia
---
## Ubuntu Commands
```bash
# check file size of two levels
cd ~
du -h -d 2
```

## Nvidia
```bash
dell: F12 or ctrl+alt+F1 or ctrl+alt+F2
sudo vim /etc/modprobe.d/blacklist-nouveau.conf
# add 
blacklist nouveau
options nouveau modeset=0
# regenerate initramfs
sudo update-initramfs -u
```
## References

<!-- https://blog.csdn.net/zxxxiazai/article/details/101073854#commentBox
<p id = "build"></p> -->
---
