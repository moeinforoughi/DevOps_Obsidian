A part of [[DevOps]] learning path
 A part of [[Docker]]

- Docker Engine
	- It needs Linux kernel to handle containers base
- Docker Host
	-  The place for deploy Docker engine
- Docker Client
	- The CLI that connect you with Docker daemon
- Registry
	- The place to put and hold our images ( *pull and push* )
	- We have private and public registries
	- `hub.docker.com` A public registry to upload your images on your repositories or using others images 
- Images
	- A template of our product with all libraries it needed
	- Read-only and moveable
	- Images are set of the layers that container stay ahead of all the layers and it's writeable and readable and run the process 
	- ![[Image Docker Images Topology.png]]
- Docker Workflow
- ![[Image Docker Workflow Topology.png]]
- Container Format
	- It's for contributing between other containers 
- Docker Compose
	- This option help us to run command to multiple action on multiple containers
- Docker Swarm
	- This default Docker orchestration that help you mange multi host networking and manage multiple servers
- Docker Machine
	- Creates VMs that have Docker daemon on them to make Docker labs
- Kitematic
	- An GUI for Docker




![[Image Docker Component Topology.png]]
