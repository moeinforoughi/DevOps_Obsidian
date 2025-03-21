A part of [[DevOps]] learning path
 A part of [[Docker]]

- Connection with other containers ,host , other host and other host containers
- Docker network drivers
	- Bridge -> A driver that make a bridge between containers network drivers and host network driver
	- None -> A driver that help us to make isolated container without any connection with outside 
	- Host -> A driver that use the host network driver also for container 
	- MacVlan -> This driver use for legacy network setup like VMs and give the container a IP in range of host IP range ( *Hardly useable* )
	- Overlay -> Help us to manage multi host networking 
	- ![[Image Docker Network Topology.png]]
- Also you could install other network driver plugin for your docker  
- A container also could have more than one driver but they shouldn't conflict each other ( *For example you couldn't have a none network driver with a host driver or bridge driver but you could have five bridge driver* )
- Port Management
	- Expose port -> When a port only got listened only inside docker container 
	- Publish port -> When we map a port of container to a port in host and container could listen the port from host 
	- We must not publish ports if we don't really need them because of the security reasons
- DNS Management
	- Internal DNS between containers to make communicate of them more easier with their names and host names and IDs and IPs
	- ![[Image Internal DNS Topology.png]]
- Docker automatically manage your host IPtables and write rules 
- Running DNS
	- Create a new network driver with `Docker network create NAME` 
- You could