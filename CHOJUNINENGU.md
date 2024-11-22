1: A and C
2: 
| BIOS     |   UEFI   |
|----------|-----------|
| IT short for basic input output system | It is short for unified extensible firmware instaface|
|It supports just 4 partitions | it supports 128 different partitions|
|


3: you can check the kernel module by running `lsmod`
   ###### to load a new module known as `dummy`,
  since we already have the module name we want,you use the comman ```sudo modprobe dummy``` to load it into memory
  create a dummy  network using the command ``` sudo ip link device_name type  dummy ```
  you can then set it up using ``` ip link show devic_name up```

  4: 
  # the proc 
  it provides info on running processes
  contains files and directory for proccessed

  # the sys
  it represents divices and drivers as files ( some cases directories)
  allows users and programs to query or modify hardware setting when the system is running

  # SECTION 2
  5: B and C
  6: 
  | apt |  dpkg  |
  |------|----------|
  |this is an advanced PACKAGE MANAGER | it is a low package manager|
  | ADVANCE PACKAGE TOOL | DEBIAN PACKAGE MANAGER |
  | it takes packages directly from the repo | does no fetch packages from the repository |
 
  7:
   ``` dpkg --purge package_name```
   8: 
   Inorder to configure a yum repository,you must first edit the configuration file 
   you use the ``` sudo nano /etc/yum.repo``` then you can add your desired repo link

   #  section 3
   9: B

   
   10: ``` grep "error" | wc /var/log/syslog```

   
   11: 
   | hard links | soft links |
   |-------------|------------|
   | it points to thesame inode as the same file | point to different inode as the file |
   | it can go accross a different filesystem |  it can go accross a different filesystem |
   | when the original file is deleted,it has no effect on the hardlink | when the original file is deleted,the softlink is broken|
   | you can use the ``ln`` command to create a hardlink | you can use the `` ln -s`` to create a softlink with the "s" indicating that it is a softlink |
    12 : ````sh find /etc .conf f -mtime -7 ```


  13 : a cron deamon is used to run specific background task which is scheduled for specific time intervals
      it is writen in the format * * * * *  with each asterix representing a specific measure of time
| asterix | meaning |
|----------|---------|
| 1 | min|
| 2 | hour | 
| 3 | day of month | 
| 4 | month | 
| 5 | day of the week | 

a job that runs  a backup scritp  at every midnight " ``` 0 * * * *  backup.sh  ``` "
# section 4
14 : B

 15: ``blkid``

 16:  
 | ext 3 | ext 4 |
 |--------|--------|
 | its maximum  file size is 2 terabyte | its maximum file size is 16 terabyte |
 | its filesystem size is 16 terabyte | its filesystem size is 1 exabyte |


17: ______________________
18: the /etc/fstab is a file systemtable

     
   
