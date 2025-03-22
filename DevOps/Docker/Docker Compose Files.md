A part of [[DevOps]] learning path
 A part of [[Docker]]

- After we build images with docker file docker compose file help us to run the containers  and setup containers network, volumes
- `compose.yml` or `compose.yaml`
- Syntax
	- `Build` -> You can build a image
	- `Command` -> You could set commands ( *the command we were write after container name in docker run command* )
	- `Container Name` -> You could set your container name
	- `Depend on`-> Pend a container to another container
	- `Network`-> Set network 
	- `Volume`-> Set volume
	- `Restart`
	- `Label` ->To set labels
	- `Environment variable` -> Set environment variables
- Structure
	1- Version
	2- Define resources ( *network, volumes* )
	3- Using resources