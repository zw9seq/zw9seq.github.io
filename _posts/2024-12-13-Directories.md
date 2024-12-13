---
title: System Directories
date: 2024-12-13 10:38:00 +0800
categories: [Linux_Basics]
tags: [directories]
description: Review of the Unix-like system's directories.
#media_subpath: /path/to/media/
#pin: true
---

## Linux System Directories

- **/** -> Root directory of the file system. All files and directories are located under this directory.

- **/bin** -> Contains essential binaries for the system, such as basic commands required for system operation and recovery in maintenance mode (e.g., ls, cp, mv).

- **/boot** -> Contains files necessary for system boot, including the system kernel (vmlinuz) and bootloader configuration files (grub).

- **/dev** -> Contains device files that represent hardware and peripherals of the system, such as hard drives, terminals, and other devices.

- **/etc** -> Contains system and application configuration files, such as network and user configuration files.

- **/home** -> Contains users' personal directories. Each user has a subdirectory here (e.g., /home/user).

- **/lib** -> Contains shared libraries essential for the binaries in /bin and /sbin. Includes support libraries for the system and basic applications.

- **/media** -> Mount point for removable media such as CD-ROMs, DVDs, and USB drives.

- **/mnt** -> Temporary mount point for manually mounted file systems. Used for temporarily mounting disks or partitions.

- **/opt** -> Contains additional software packages that are not part of the base system. Often used for third-party applications.

- **/proc** -> Virtual file system that provides information about the system's state and running processes. It does not contain real files but provides a dynamic view of kernel information.

- **/root** -> Home directory of the root user. Similar to /home/user, but for the superuser.

- **/run** -> Contains data about the system at runtime. Includes information about the system state and running services.

- **/srv** -> Contains data for services provided by the system, such as web or FTP servers.

- **/tmp** -> Contains temporary files created by applications and the system. These files are usually deleted automatically upon system reboot.

- **/usr** -> Contains applications and support files for users. It is divided into subdirectories such as /usr/bin (binaries), /usr/lib (libraries), and /usr/share (shared data).

- **/var** -> Contains variable data files that change over time, such as system logs (/var/log), emails, and temporary files (/var/tmp).

- **/dev/urandom** -> A source of pseudo-random ASCII characters.

