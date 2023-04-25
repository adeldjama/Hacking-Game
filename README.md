# Hacking-Game

## Goal

Your Mission, Should You Choose To Accept It, is to take control of the Contoso domain controler. To reach this goal, you have to excute the diffrent step of the plan described bellow using the tools provided in the toolbox section. You have to determine which tool should be used in

## Provided Environment 

There are 3 VMs: lab-vm (Windows10), workstation-vm (Windows10) and dc-vm (Windows Server 2016) 


## Hacking Steps

1- Connect to lab-vm using RDP (The Public IP address and credentials will be provided by the coach)

2- Discover the private IP address of workstation-vm using a tool that you have in the toolbox

3- Find the credentials (login and password) that allow you to connect to workstation-vm using RDP

4- Connect to Workstation-vm using RDP

5- Discover the IP address of the domain controller using one tool in the toolbox  

6- Find the login and the password hash of the Admin Domain using one tool in the toolbox

7- Connect to the domain controller using RDP 


Note every tool is used one time 

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

