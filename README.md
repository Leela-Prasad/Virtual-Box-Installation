Install Guest ISO:

Download ISO file from below location
"http://download.virtualbox.org/virtualbox/5.1.30/VBoxGuestAdditions_5.1.30.iso",

Then we have to attach this ISO to Virtual box
Virtual box - settings - storage - controller:SATA - add optical drive(iso) here.

Now start your machine and run the ISO file
Go My Computer and under devices section this iso will be available, run it.

Restart the System.

Reference Links: 
https://github.com/udacity/devops-intro-project/issues/52

How to configure Shared Location:
Virtual box - settings - Shared Folders - add a location
** After adding the location Double click on the location and select Auto-mount checkbox.

Now login to the system and open a terminal
Run below command
sudo usermod -aG vboxsf $(whoami)

Restart your machine.

Reference links: 
https://askubuntu.com/questions/456400/why-cant-i-access-a-shared-folder-from-within-my-virtualbox-machine
