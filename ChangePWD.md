How to change the default password of root
If you get below error while SSH then change default password of root.
 
Switch from administrator to root
Sudo -i
 
Edit the SSHD file
sudo nano /etc/ssh/sshd_config
edit the file with 
PermitRootLogin yes
 
Press Ctrl X and hit enter
 
Change the root password
Sudo passwd root
 
Restart the system
Sucessfuly logged in with SSH with root



