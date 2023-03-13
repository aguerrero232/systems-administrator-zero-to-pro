# <img src="../assets/img/network.png" width="30px"> **Systems Administrator** - ***Section 0:*** `Resources` 🗃️



## Linux File System

The Linux file system is a hierarchical structure that organizes files and directories into a tree-like structure. The root directory is the top of the tree and all other directories and files are organized below it. 


**Standard Linux File System Hierarchy**

```bash
/
├── bin -> usr/bin
├── boot
├── dev
├── etc
├── home
├── lib -> usr/lib
├── lib32 -> usr/lib32
├── lib64 -> usr/lib64
├── libx32 -> usr/libx32
├── lost+found
├── media
├── mnt
├── opt
├── plugins
├── proc
├── root
├── run
├── sbin -> usr/sbin
├── snap
├── srv
├── swap.img
├── sys
├── tmp
├── usr
└── var
```

* to view this tree structure, run the following command in your terminal:

    ```bash
    tree -L 1 /
    ```

    * `-L 1` limits the depth of the tree to 1 level using `/` (the root directory) as the starting point



* **/boot** - contains the Linux kernel and boot loader files
* **/dev** - contains device files that represent hardware devices
* **/etc** - contains system configuration files and stands for "extended text configurations"
* **/home** - contains user home directories
* **/root** - contains the home directory for the root user
* **/var** - contains variable data that changes over time
* **/usr** - contains installed software, shared libraries, including files, and read-only program data
    * **/usr/bin** - contains executable programs for all users
    * **/usr/sbin** - contains executable programs for the systems root user, and requires root privileges to run
* there are also two forms of temporary storage:
    * **/tmp** - contains temporary files that are preserved between reboots
    * **/var/tmp** - contains temporary files that are not preserved between reboots








<br />

[↩️](../README.md)
