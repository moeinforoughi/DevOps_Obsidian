A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

1-  `ps -aux | grep nginx`   Showing the process of Nginx service
2- `sudo kill -9 27213`      Killing process with Id of 27213
3- `pidof nginx`   Showing all the processes that depend on Nginx
4- `pidof nginx | xargd suod kill -9` Xargs command taking the answer of last command after that kill all the processes
5- `iotop` Showing witch process using IO
6-`jobs`  Showing user processes they running on background
7- `bg `  and `fg`  Sending and process to background or foreground 




Recommanded by myself =>

5- `htop` More beautiful and more graphical interface for showing processes and hardware usage

