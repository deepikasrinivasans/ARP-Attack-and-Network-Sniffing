# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

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
![1E](https://github.com/deepikasrinivasans/ARP-Attack-and-Network-Sniffing/assets/119393935/9af93efb-7f0d-45e5-98e6-c30df12337a4)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2E](https://github.com/deepikasrinivasans/ARP-Attack-and-Network-Sniffing/assets/119393935/b8c36799-aae7-4a94-aea1-f6e32f1cd4fb)
## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3E](https://github.com/deepikasrinivasans/ARP-Attack-and-Network-Sniffing/assets/119393935/49c85e5a-fc70-4f46-a84a-2c2396b519b5)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![5E](https://github.com/deepikasrinivasans/ARP-Attack-and-Network-Sniffing/assets/119393935/1e3b099e-0ad4-43eb-9ee9-cb839461d47a)
Invoke the wireshark and examine the various menus  and controls of the tool:
![4E](https://github.com/deepikasrinivasans/ARP-Attack-and-Network-Sniffing/assets/119393935/a00c61ca-c2b4-4eeb-acc1-9e348a3de511)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
