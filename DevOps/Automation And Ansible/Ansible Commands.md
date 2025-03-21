A part of [[DevOps]] learning path
 A part of [[Automation And Ansible]]

- Install Ansible from official website of ansible on your controller node
- `vim ~/.ansible/ansible.cfg` or `vim /etc/ansible/ansible.cfg` Address of Ansible config file to change configuration 
- `ansible localhost -m ping` Make a SSH connection to local host and shows pong massage if connection was okay 
- `ansible-galaxy init ROLENAME` Make a full directory of role automatically for user
- `ansible all -i inventory/hosts.yml -m ping` Ping your hosts in `hosts.yml` file
- ==`ad-hoc commands`== -> Commands we run out of playbook that just for checking status and simple tasks
- `asnible-playbook -i INVENTORYADDRESS PLAYBOOKNAME` Run your playbook 
- `ansible HOSTNAME/IP -m setup` Shows all variable of nodes or host ( Gather Fact )
- `-m` Option to add modules to our command
- `-a` Option to add options of modules to our command 
- `ansible HOSTNAME/IP -m setup -a "filter=os_family"` This example give us OS of the host variable ( We could use it to gather other information about the host )
	-Ansible options
			1- `--check`  Before run and action with ansible this option just check tour manage nodes
			2-`--diff` Shows the difference after and before running ansible
- 