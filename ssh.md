# How to SSH into Lab Workstations

## Initial SSH Config
Download VSCode for your machine here: https://code.visualstudio.com/download

Click the arrow brackets at the bottom left corner of your screen
![ssh_1](https://github.com/ialab-yale/Lab-Startup/blob/main/images/ssh_1.png)

Click "Connect to Host" on the dropdown menu

Click "Add New SSH Host"

Type "ssh \<IP-address-of-computer\>"

Press enter until you see a dialog box pop up that says "Host added!"

Your host is now added

## Open SSH

Click the arrow brackets at the bottom left corner of your screen

Click "Connect to Host"

Click the item in the menu that is the IP address of the machine you want to SSH into

It may prompt you to enter your password. If so, enter the password to your account on the workstation

You should be connected!

## IP Addresses

IP address of Squirtle (Blue lights): 172.27.52.193

IP address of Bulbasaur (Green lights): 172.27.196.118

IP address of Charmander (Red lights): 172.28.141.13

## Troubleshooting

You may run into the issue of not being able to connect to your own account when SSHing

To fix this, press the arrow brackets at the bottom left corner of your VSCode screen

Click "Open SSH Configuration File" and press enter

You should see something that looks like this
![ssh_2](https://github.com/ialab-yale/Lab-Startup/blob/main/images/ssh_2.png)

For the appropriate host, make sure to add the "User" field with the username of your account on the workstation