$ ./make_mx5bull

0. Linux shall be built and configured in advance!!

1. Make copies all needed files into build_linux-5.13.5_conf_2 from
   - linux-5.13.5_conf_2			- configured linux
   - disk.u-boot-imx_2021.01-rc.3 fs-ext4	- u-boot

2. Make updates, adds and replaces certain files in build_linux-5.13.5_conf_2 from
   - rootfs_mx5bull - from git repo (git.linux_settings_bullseye)

3. Writes into /dev/sdb
   - u-boot
   - zImage
   - DTB
   - ROOT-FS
