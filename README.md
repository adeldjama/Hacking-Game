# Hacking-Game

## Goal

Your Mission, Should You Choose To Accept It, is to take control of the Contoso domain controller. To achieve this, follow the steps below. We've provided three tools in the toolbox section to help you unlock some of the steps. However, you'll need to identify the appropriate tool to use for each step. 

## Environment 

There are 3 VMs: hack-vm (Windows10), workstation-vm (Windows10) and dc-vm (Windows Server 2016) 

![archi](./images/archi.jpg)
## Hacking Steps

1- Connect to the hack-vm using RDP. Your coach will provide you with the Public IP address and credentials.

2- Use a tool from the toolbox to discover the private IP address of the workstation-vm.

3- Use a tool from the toolbox to find the login and password that will allow you to connect to the workstation-vm using RDP.

4- Connect to the workstation-vm using RDP and the login and password found in step 3.

5- Discover the IP address of the domain controller.  

6- Use a tool from the toolbox, (a) to find the login and password hash of the Domain Admin then (b) to connect to the domain controller using RDP.


  >**Note**: Each tool should be used one time  

## Toolbox
1- Mimikatz 
- https://github.com/ParrotSec/mimikatz
- https://techyrick.com/mimikatz-tutorial/
- https://edermi.github.io/post/2018/native_rdp_pass_the_hash/

2- Nmap 
- https://nmap.org/download.html

3- Hydra 
- https://github.com/maaaaz/thc-hydra-windows
- https://securitytutorials.co.uk/brute-forcing-passwords-with-thc-hydra/
- https://github.com/adeldjama/Hacking-Game/blob/b3d41fc73a9daface2a8ae1d90f7175e5890be0b/username.txt
- https://github.com/adeldjama/Hacking-Game/blob/ea7262ec5cd3b8a07c9e1df77d5e4f627f39d940/password.txt

