A part of [[DevOps]] learning path
 A part of [[Docker]]

- ![[Image Docker Volume Topology.png]]
- The ways you could extract data from container
	- Using mount points -> Map a directory inside the container with a directory into host(*This way has some problems most important problem is permission access*)
	- Using Docker volume -> We create a new volume and map this new volume with a path inside the container (*It has permission management*)
- Docker volume commands 
	- `Docker volume create` -> Create new volume
	- `Docker volume ls`-> List your volumes
	- `Docker volume prune`-> Remove unused volumes
	- `Docker volume rm` -> Remove volume
	- `Docker volume inspect`-> Show a lot of detail about volumes 
- Docker run command volume management
	- `Docker run -v my_data:var/lib/mydata`
		- `my_data` Is the name of the volume\
		- `var/lib/mydata` The direction inside the container that connected to the volume
- Using this volume management config help us to manage our containers data if we at first time ==make a container and connect it to a volume when we delete the container we don't lose our data and if make a new container with these volume the new container contain the data until we delete the volume== 
- *We could also store our data to remote and external storages with Docker volume drivers*