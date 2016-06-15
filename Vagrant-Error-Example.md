
#Vagrant Error Example

#### Error 1 => 
VirtualBox is complaining that the kernel module is not loaded.
<pre>
vagrant up
The provider 'virtualbox' that was requested to back the machine
'default' is reporting that it isn't usable on this system. 
The reason is shown below:

VirtualBox is complaining that the kernel module is not loaded. Please
run `VBoxManage --version` or open the VirtualBox GUI to see the error
message which should contain instructions on how to fix this error.
</pre>

####Solution
Just run bellow command after that vagrant up again.
<pre>
sudo /etc/init.d/vboxdrv setup
</pre>
