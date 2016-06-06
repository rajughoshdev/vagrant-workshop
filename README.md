# Vagrant
Vagrant is an excellent open  source tool for managing virtual machines. Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

##Vagrant Commands List

<pre>vagrant init [box-name] [box-url]</pre>
Initializes the current directory to be a Vagrant environment with.vagrant directory if does not already exist. 

<pre>vagrant up </pre> 
For the starting the  machine to create an enviroment.  

<pre>vagrant status</pre>	 
For the showing machine status that is open or not. 

<pre>vagrant halt </pre>
For the closeing the machine.

<pre>vagrant suspend </pre>
For the suspends a  machine (remembers state).

<pre> vagrant provision</pre>	
For the forceing reprovisioning of the machine

<pre>vagrant reload </pre>
For the restarting the machine with loads the new Vagrantfile configuration.

<pre>vagrant ssh </pre>	
For the connecting to machine via SSH

<pre>vagrant share </pre>
For the sharing your VM and provides you with the public URL

<pre>vagrant login </pre>	
Log in to HashiCorp's Atlas on your computer

<pre>vagrant destroy </pre>	
For the deleteing the machine. 

<pre>vagrant -v </pre>	
For the knowing  the version

<pre>vagrant global-statu </pre>s	
For the knowing state of all active environments on the system for the currently logged in user.

<pre>vagrant resume </pre>	
For this resumeing a suspended machine (vagrant up works just fine for this as well)

<pre>vagrant reload --provision </pre>	
For the restarting the machine and force provisioning.

<pre>vagrant push -- Yes </pre>	
For the configuring to deploy code. 

<pre>vagrant up --provision</pre>	
For Runing vagrant up and forces provisioning. 
