**Step 1:** Insert the XenTools ISO in the DVD drive of the Linux VM

**Step 2:** Mount the DVD drive to */mnt* using:

*mount /dev/xvdd /mnt*

It says, *mount : block device /dev/xvdd is write-protected, mounting read-only* 

If */dev/xvdd* is not working then try:

*mount /dev/cdrom /mnt*

**Step 3:** Change the directory to */mnt*:
*cd /mnt*

Then list the contents using:

*ls*

Change the directory to */Linux* using:

*cd Linux/*

Use *ls* to list the contents again.

**Step 4:** Use *./install.sh* to install the XenTools

*Continue? [y/n] y*

**Step 5:** XenTools should show optimized 

**Step 6:** Reboot the VM once. 

