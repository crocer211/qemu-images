# Damn Small Linux v4.11.rc1

Link: https://drive.google.com/open?id=1GUcR39YhaFop6IirS6b4wc4OOMT7pAcs

Extract dsl-4.11.rc1.7z for the disk image. Run in QEMU with the following: `qemu-system-i386 -hda dsl-4.11.rc1.qcow2`

## Install Info
- 1 GiB in total virtual size

The install is so fresh that users have not even been setup.

Here are the steps to take when you first run the system:
1. It will prompt you for a new password for `root`. Enter a new password.
2. It will then prompt you for a new password for user `dsl`. Enter a new password.
3. It will then prompt you with `box login: `. Enter `dsl` then enter the password you gave `dsl` earlier.
4. In a few more seconds it will boot up with a graphical desktop.

If you would like to setup APT for debian packages, see here: https://owenthe.ninja/2016/07/getting-apt-on-damn-small-linux-in-2016/
