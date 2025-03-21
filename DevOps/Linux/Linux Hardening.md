A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

- Hardening -> How to make our Linux more secure
1- Separating partitions form each other `/boot` , `/` and `/var`
2- Storage sharing must be like if we have 100GB of storage 2GB -> `/boot`  , 30GB -> `/` , 68GB -> `/var` 
3- Being updated ( specially security updates )
4- Check packages in period and versions ( we must have list and versions of packages and hardly must install packages )
* We never install compilers on Linux servers 
5- Port scanning in a period ( mostly just SSH allowed to be open )
6- We must completely config and secure our SSH 
7- We must set a good password policy 
8-Secure physical accesses to servers 
9- Config IP tables and firewalls on your Linux
10- Log your logins and config your authentication 
11- Send logs out of the servers 
12- Failed to ban for prevent brute forcing 