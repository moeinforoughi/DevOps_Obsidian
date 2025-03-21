A part of [[DevOps]] learning path
 A part of [[Docker]]

- Syntax
	- `FROM` You can select a base image for your image 
		- *`FROM` must  be the first thing in docker file and nothing could stand before it( may `args` )
	- `LABEL maintainer='Moein Foroughi'` You could add name of the author of the container
	- `RUN` You could run commands during the image building time (*like updates and installations* )
	- `CMD` You could run commands after building ends and in container mode 
	- `EXPOSE` You could config the ports that container needs to listen to them (*mostly its like a metadata that shows port usage of the container* )
	- `ENV` You could set environment variables 
	- `ADD` and `COPY` 