##INSTUCTIONS
**Retrive and install 'storaAIO.sh"**

```` bash
-bash-3.2$ wget --no-check-certificate https://github.com/darkfire/Stora-AIO/raw/master/storaAIO.sh
-bash-3.2$ chmod +x ./storaAIO.sh
-bash-3.2$ sudo ./storaAIO.sh
````

**Run selected tasks**

1. Setup the PATH variable/environment
2. Swap the SSH Daemon with a clean version
3. Install the IPKG Package Manager
4. Move /opt to the harddrive
5. Install Kernel NFS
6. Remove Access Patrol
7. Install NZBget
8. Install NZBget-server
9. Install Transmission

I would suggest running the first three. This will help setup you system for easier shell use in the future. 

*Task 3* allows for a simpler ssh login.
For example;

```` bash
jude@jude-desktop$ ssh jude@192.168.1.3
````
*Task 4* moves /opt to the hard drive. You may find yourself installing other things on the box. This allows you to not have to worry about space limitations.
