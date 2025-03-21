A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

- `find DESTINATION/FILE | grep WORD` At first find a file in a directory after that find word in this file 
- `echo WORD > FILENAME` Redirect the word into the file ( *Its delete all data in file and write word in file* )
- `echo WROD >> FILENAME` Append word to the file 
- `vmstat` To check your virtual memory using
- `iotop` To check your IO status 
- `tar -czf FILENAME.tar.gz FILENAME` To compress a file first filename takes the new file name and the second file name takes the file name that you want to compress 
- `file FILENAME` Shows what is this file 
- `dd` You could make random files with a specific storage and can copy files ( *read more about this for using )
- `watch COMMAND DICADDRESS` Every 2 second run a command that you said in directory you said 
- `wich PACKAGENAME` Shows that a package exist or not and shows the installed path 
- `whereis PACKAGENAME` Shows addresses of the package files 
- `whatis PACKAGENAME` Shows what is a package
- `man PACKAGENAME` Shows MAN pages of packages
- `info PACKAGENAME` Its like MAN pages 
- `uname` Shows system information 
- `lsb_realease` Shows data about your Linux that installed 
- `env` Shows your system environment variables 
- `export WORD=ANY` You could make new environments variables with this command
- `echo $WORD` Show the variable with name word
- `xargs` Takes answer of last command you could do anything with them 
- `ulimit` You could make user limits with this command
- `chroot` You could open command line from a different root user 
- `lsmod` List modules of the Kernel `lspci` List your PCIs `lsusb` List your USB devices
- `htpasswd` Create and set user and password for web authentication 
- `nmap` For port scanning for security usage 
- `openssl` For working with certificates 