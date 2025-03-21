A part of [[DevOps]] learning path
 A part of [[Automation And Ansible]]
 
	File stracture ->
			myplaybook.yml
			inventory
					group_vars
					hosts.yml
					hosts_vars
			roles
					test
						defaults
							main.yml
						files
						handlers
							main.yml
						meta
							main.yml
						tasks
							main.yml
						templates
						tests
							inventory
							test.yml
						vars
							main.yml
						README.md
				
				

- ==`hosts.yml`== -> Contain serves address , ports ,users and everything about servers 
- ==`myplaybook.yml`== -> Tells what action must done on which servers
- ==`group_vars`== -> Contain group variables to change them easier in 
- ==`hosts_vars`== -> Contain special variables to do something special in a special server 
- ==`Roles directory`== -> Contain data about role that I will explain below 
	- `default` -> Contain default variables of a role
	- `files` -> Good for to transfer a file to manage nodes that doesn't have any variables and changes 
	- `template` -> Good for transfer files to manage nodes with changes per server and different variables 
	- `handlers` -> When we have to restart a service after changing handler can restart your services after all changes done successfully 
	- `test` -> Just to set tests 
	- `meta` -> Add meta data
	- `vars` -> We could add variables but with existence of default directory its not so efficient
	- `tasks` -> It's so important directory that contain tasks (*if we have a lot of tasks we could give links to some other files that they contain tasks)
