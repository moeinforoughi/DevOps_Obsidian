
A part of [[DevOps]] learning path

- Docker using Linux native options to build this environment the Linux option called ==`Nmaespaces`== Docker build a namespace for every app in Linux kernel that they run in a ==isolated environment== from other app so at this point we have our ==Isolation== and ==Limitation== 
- ![[Image Namespaces Topology.png]]
- Docker using ==`CGroups`== from Linux native options that helps Docker to ==share resources== between the containers those are running in namespaces 
- ![[Image Cgroup Topology.png]]
- Docker using `UnionFS` Option 
	- ==`UnionFS`==
		- Layering 
			- Docker automatically find same layers in different images so doesn't copy them again and use a similar layer for different containers and images  ( *for example when you have a Ubuntu image on your storage Docker Doesn't download and copy it twice and use the similar layer* )
		- COW ( Copy On Write )
			- When you build an container in Docker the COW option give you more speed because the image that it built the container from it doesn't need to be copied because it's a read-only file and we can't do any changes on it so just make a layer for write ( *because of this you can delete or remove the image until your containers is up* )
		- Caching
		- Diffing
- ![[Image UnionFs Topology.png]]

- Docker Topology
![[Image Docker Topology.png]]
![[Image Docker vs VM.png]]



