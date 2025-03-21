A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

- `vim ~/.ssh/authorized_keys` Shows your trusted key lists
- `cat .ssh/id_rsb.pub` Shows your public key 
- `ssh-keygen` Make a new SSH key for you
- `cd etc/ssh/ssh_config` and `sshd_config` You could config your SSH
- `sshd -t ` After changing your configs this command check your config file for errors
- `systemctl restart sshd` Restart the service to save changes 
- `ssh moein@192.168.1.10 -p 8090` SSH to IP 192.168.1.10 with port and user Moein 
- You could config users and groups accesses with adding `AllowUsers` and `AllowGroups` to your config file 
- At end there are a lot to learn about SSH config file 