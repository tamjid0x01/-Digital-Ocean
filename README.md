# -Digital-Ocean
### Install Windows 10 on Digital Ocean

Steps:

1- Create a New Ubuntu Droplet

2- Turn off the machine

3- Set recovery mode to boot from ISO

4- Turn On The machine

5- Run Interactive Shel (6)

6- Set the root password using the following command:

sudo passwd root

7- Connect to your Machine using Putty – [Download From this link](https://computech21.com/2019/05/22/download-putty-free-ssh-client/)

8- Run the Windows Deployment Command:

For Windows 10:

wget -O- https://www.dropbox.com/s/e2oglmh3tdu3boz/WIn10.gz?dl=1 | gunzip | dd of=/dev/vda

For Windows 2012:

wget -O- https://www.dropbox.com/s/eiductyclyf7kve/WinServerImageDO.gz?dl=1 | gunzip | dd of=/dev/vda

9- After the command finishes, turn off the machine and set it back to boot from hard disk in the recovery section in the digital ocean droplet management dashboard.

10. Turn on the droplet.

11 – Login with the following user and password:

username: WhatUpTime.com
Password: P@ssword64

Configure Networking, set the IP, SubNet, and the gateway as given in the console window in the right corner.

12  – Done, Connect with RDP Client.

Link ::: [youtube](https://www.youtube.com/watch?v=cgkjjJA8rGc)


## configuring putty 


