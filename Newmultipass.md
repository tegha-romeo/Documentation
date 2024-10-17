# Multipass Documentation
## Definition :
* Multipass is CLI to launch and manage VMs on windows, MAC, and linux to stimulate cloud environment with support for cloudinit  
 * Multpass has a docker blueprint that gives its users access to out-of -box docker on any platform.
 ##   How to install multipass
 * To  install multipass we use the command
***command*** : 
**sudo snap install multipass**
###   Launch Docker on a virtual machine, VMs
* after installing multipass create a VMs using the command 
***command***
**multipass launch docker --name instance**
The above command creates a VM with docker and portainer instaled
to **test this** use the command below
***comand***
**multipass exec docker-name --docker ps**
## Alias of Docker command
* An alias is alike shortcut use to run a container in your docker environment
* This mean that it makes it faster and easier to run lengthy commands
* In are command above we would write as such
***command***
**alias docker name="intance name" --docker ps**
## Conclusion :
* Working with virtual machines can be very interesting
