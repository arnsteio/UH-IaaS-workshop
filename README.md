# UH-IaaS-workshop

Time: 3 hours
 
Prerequisites: Knowledge of the Linux command line

## Course content:
1. [Background](01-intro.pdf)
2. [Initial GUI login, and making a server](02-makingServer.md)
  * Log in, get API password
  * Set up SSH keys
  * Add SSH keys to OpenStack
  * Add security groups to OpenStack
  * Make a server
3. [Let's log in on our machine!](03-initialLogin.md)
4. [Attaching storage](04-AttachingStorage.md)
  * Make keystone.sh setup file
  * Making storage via CLI
  * Attaching storage via CLI
5. [Initializing storage](05-initializingStorage.md)
  * Making a file system
  * Mounting the file system and storing some data
6. [Transferring storage] 
  * Installing openstack-cli on your own machine
  * Deleting the machine we made
  * Make a new machine
  * Exercise: Mount the volume on this machine

## Web site:
<https://arnsteio.github.io/UH-IaaS-workshop/>

## Notes on teaching
Participants should be given the URL of the web site immediately, this will save typing. 
This workshop is very helper heavy. 

## Notes on structure
External participants get CLI access, not GUI access.
UiO-internal participants should follow the workshop as it is set out above.
Others should get help installing openstack-cli (6) while we do GUI stuff in plenary.
They will be issued a keystone.sh file for the course project and can follow the workshop in CLI.
Main problem will be adding SSH keys and security groups. 
This is easy via CLI if you are following the recipe provided on <02-makingServer.md>.

