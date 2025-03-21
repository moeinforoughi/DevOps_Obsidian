A part of [[DevOps]] learning path
 A part of [[Automation And Ansible]]

- ![[Image Ansible Topology.png]]
- ![[Image Ansible Topology 2.png]]

- We selected Ansible between `Chef` , `Papet` and `SaltStack` 
- `Terraform` is something different and shouldn't compare with Ansible
- Ansible is Python base and developing by RedHat 
- Ansible connect with SSH to our nodes and config them 
- ==Controller Node== -> Is like our laptop or a machine to control nodes 
- ==Manage Node== -> the nodes we could manage them with Ansible
- ( *its better to put controller node near the servers for better connection* )
- ==Inventory== -> A place to put the manage nodes connection information to help Ansible connect to them 
- ==Playbook== -> A place to tell Ansible witch configuration is for witch manage node holds the rules names and nodes names
- ==Rules== -> Contain tasks that must be done on manage node
- ==Groups== -> We could make groups like databases , servers , backends 
- We could make rules for groups and single nodes 
- Bastion -> Bastion is a middle server to access to private servers with asnible
- ![[Image Bastion Host Topology.png]]
- ==Tag== -> We can give any tasks a tag and we want just run a group of tasks we can use their tag names 