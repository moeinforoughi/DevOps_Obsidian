A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

**1- Add new storage to your machine** 

- After resizing the physical size of your disk and storage you must do it for your partition with (LVM) 
- `apt install lvm2` installing LVM packages 
- `lvm`,`vgs`,`lvs` commands to see detail of an LVM storage machine
- Add more storage with VirtualBox settings
-   Manage your new storage partition with [[FDISK tutorial]]
- `vgextend ubunto-vg /dev/sdb1` For adding new storage and partition to your main storage
- `lvextend /dev/ubunto-vg/ubunto-lv /dev/sdb1` Resize the disk

// These are additional for Ubuntu might be different in  other types of Linux

- `resize2fs /dev/mapper`
- `resize2fs /dev/mapper/ubuntu--vg-ubunto--lv`

**2- Mount a new storage somewhere** 
- `mkfs.ext4 /dev/sdb2` Format the storage with the 'ext4' type
- `mount /dev/sdb2 /mnt` Mount 'sdb2' storage to `/mnt`
- *After restarting all of our mount gone so we must add to `fstab` file*
- `vim /etc/fstab` 
- At the end of file before end write this => `/dev/sdb2 /mnt ext4 defaults 0 0`
- `mount -a` Test you wrote those write or not

 