# Knowledge base

Anything I find interesting or handy to keep I'll put here for reference.
There is no order, only chaos! 

## Cannot mount NTFS drive with Dolphin

When trying to mount an NTFS drive with dolphin you might run into the following error:

```Shell
wrong fs type, bad option, bad superblock on /dev/sda5, missing codepage or helper program, or other error
```

First make sure you have all the appropriate software installed:

- ntfs-3g
- ntfsprogs

When you do, it's most likely that Dolphin tries to mount the drive through an older kernel driver.

You can fix this by editing (or creating) `/etc/modprobe.d/blacklist.conf` (as a super user)
Add the following line to it:

```Bash
blacklist ntfs3
```

Reboot the system.