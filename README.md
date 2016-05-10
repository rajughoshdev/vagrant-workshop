# Vagrant-Help
Vagrant is an excellent open  source tool for managing virtual machines. Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

##Vagrant Commands List

##### vagrant init [box-name] [box-url]
Initializes the current directory to be a Vagrant environment with.vagrant directory if does not already exist. 

#####vagrant up 
For the starting the  machine to create an enviroment.  

#####vagrant status	 
For the showing machine status that is open or not. 

#####vagrant halt
For the closeing the machine.

#####vagrant suspend
For the suspends a  machine (remembers state).

#####vagrant provision	
For the forceing reprovisioning of the machine

#####vagrant reload
For the restarting the machine with loads the new Vagrantfile configuration.

#####vagrant ssh	
For the connecting to machine via SSH

#####vagrant share
For the sharing your VM and provides you with the public URL

#####vagrant login	
Log in to HashiCorp's Atlas on your computer

#####vagrant destroy	
For the deleteing the machine. 

#####vagrant -v	
For the knowing  the version

#####vagrant global-status	
For the knowing state of all active environments on the system for the currently logged in user.

#####vagrant resume	
For this resumeing a suspended machine (vagrant up works just fine for this as well)

#####vagrant reload --provision	
For the restarting the machine and force provisioning.

#####vagrant push -- Yes	
For the configuring to deploy code. 

#####vagrant up --provision	
For Runing vagrant up and forces provisioning. 
