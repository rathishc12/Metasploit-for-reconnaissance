# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

### STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![241191941-6d5faf03-5344-44ab-ac2c-fd763111f491](https://github.com/Yogeshvar005/ARP-Attack-and-Network-Sniffing/assets/113497367/2126c09a-4a85-41e0-826a-cbb3b87964b9)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![241191984-a70b28b6-7f35-43b5-92d7-840f43f1bf82](https://github.com/Yogeshvar005/ARP-Attack-and-Network-Sniffing/assets/113497367/61253e4a-2dd8-41a2-a8a1-caeea1b3b1c7)

### dsniff:






#### In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![241192115-e985ae01-13fa-42f1-8155-94b04deddecb](https://github.com/Yogeshvar005/ARP-Attack-and-Network-Sniffing/assets/113497367/79ab5047-07f1-4d6a-a5f4-d5b4f503a54b)

### In Kali issue the following commands: sudo dsnifff
## OUTPUT:

![241192115-e985ae01-13fa-42f1-8155-94b04deddecb](https://github.com/Yogeshvar005/ARP-Attack-and-Network-Sniffing/assets/113497367/3472bd7e-2fc7-4e86-a6ef-d341c0476926)


### Invoke the wireshark and examine the various menus  and controls of the tool:

![241192334-e9461986-63fa-4577-8c66-ccb63a3c56bf](https://github.com/Yogeshvar005/ARP-Attack-and-Network-Sniffing/assets/113497367/fd045287-3301-40e7-a939-39ea37d0d0c4)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
