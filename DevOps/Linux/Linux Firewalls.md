A part of [[DevOps]] learning path
 Part of [[Linux]] Basics 

- `iptables -nL` Show your rules and tables
- `iptables -F` Delete all your rules ( `-t` option shows you a specific table example : `iptables -t nat -nL` )
- `sudo iptables -A INPUT -p tcp --dport 80 -j DROP -m comment --comment "HTTP port closed"` This command block all the request over port 80 
- `sudo iptables -A INPUT -s 127.0.0.1 -j ACCEPT` Accept '127.0.0.1' to access ( * but it's important to consider the sort of rules are important first rule maybe block second rules  )
- `sudo iptables-save > ~/FILEADDRESS` Save your iptables your at a file 
- You could change Iptables config files in `etc/iptables` after restarting iptables service this service read this files for startup settings 