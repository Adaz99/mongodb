# mongodb
# Provisioning project
​
What did you need to do to provision a vm to run mongo db?
​
What did you need to do to provision a vm to:
​
- Run the node.js application?
- Use the `nology.training` alias?
- Use apache server to dirent traffic to a given port?
- How are you able to pass in the DB connection string?
​
---
​
## General Environment Questions
​
- What are development environments?
- How do they relate to an application?
​
### Virtual machines
​
- What is a virtual machine?
- What does it allow you to do?
- How have you used one?
​
### Vagrant
​
- What is vagrant?

Vagrant is a tool for working with VM's (Building and managing machine) 

- What is a `VagrantFile`?

A Ruby file used to configure Vagrant, the main function of the Vagrantfile is to describe the virtual machines requirements for a project as well as how to configure and provision the machines.
​
#### CLI commands
​
| Command   | What does it do? | When did you use it? |
| --------- | ---------------- | -------------------- |
| reload    | Reloads/reboots the VM (must use when something in the Vagrantfile is changed for them to be applied)| When i made changes to Vagrantfile and wanted to reboot the VM with changes|
| up        | Downloads everything needed to start the VM which are specified in the Vagrantfile| When i wanted to create/start up a VM|
| provision | Runs any configured provisioners against the running Vagrant managed machine| When i needed to install a new dependency without restarting my whole VM|
| destroy   | Stops the running VM and destroys all the resources that were created| When the VM is no longer needed, and want a clean state to start from|
| suspend   | Suspends the VM, rather than fully shutting it down|                      |
| ssh       | Provides full SSH access to the virtual environments, able to connect to the VM| When i wanted to configure files so that my VM is fully working  |
​
#### Provisioning
​
- What is Provisioning in relation to Vagrant?
​
---
