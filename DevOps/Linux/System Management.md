A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

1-  `systemctl status nginx` Showing status of  packages those running 
2- `systemctl restart nginx` , `systemctl start`, `systemctl stop`  Restart a service 
3- `systemctl enable nginx`   Enable a service 
4- `systemctl disable nginx`   Disable a service 
5- `systemctl is-enabled nginx` Showing its enabled or not 
5- `journalctl -xefu nginx` Showing logs of  Nginx unit
6-`vim /etc/systemd/system/docker.service.d/test.conf` We could set a configoration file for packages like docker in this example  
7- `systemctl mask`,`systemcrl unmask`  Lock a service for running  
