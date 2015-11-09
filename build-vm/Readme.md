# Contents of build-vm folder

In this folder, you will find:

* **Vagrantfile** - Contains the vagrant script to load the Ubuntu 15 Desktop VM on VirtualBox with a default memory of 2048 MB
* **vm-contents** folder - This folder contains content that will be copied over to the build VM

# Minimum Requirements for using this Vagrant Script
1. Any 64-bit OS.
2. Vagrant pre-installed.
3. VirtualBox pre-installed.

# Steps to create the VM using Vagrant

1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html) appropriate to your host OS.
2. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) appropriate to your host OS.
3. Copy the file "Vagrantfile" in this folder to your host OS.
4. Open command prompt (on Windows) or terminal (on Linux) change directories to where the "Vagrantfile" was copied to.
5. Type the following in the command prompt or terminal: vagrant up --provider virtualbox
6. The vagrant file will begin executing an at some point the VM will start up on VirtualBox. 
Please wait for the vagrant script to complete executing before using the VM.
7. To use the BabelRef plugin in a PHP project, you need to install PHP Development Tools in Eclipse. 
The instructions are provided in the desktop file "Installation.txt".

# Details of the built VM

As part of the load process, the following is loaded in the VM (as part of the Vagrant script)

1. Ubuntu Desktop 15.
  * Default username: *vagrant*
  * Default password: *vagrant*
2. Java 8.
3. Eclipse 4.2 Juno
4. Sample PHP project to test BabelRef plugin (copied to /home/vagrant/Desktop/BabelRef PHP Project)