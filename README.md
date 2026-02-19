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

<img width="683" height="283" alt="image" src="https://github.com/user-attachments/assets/e46efce8-377c-465e-8bec-6fd4c2000f7a" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="1028" height="537" alt="image" src="https://github.com/user-attachments/assets/f9804f18-bc3c-4cfc-8638-1a200ae47588" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="778" height="437" alt="image" src="https://github.com/user-attachments/assets/4d1059e0-0e58-40f2-aa33-038116b70bb3" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="364" height="116" alt="image" src="https://github.com/user-attachments/assets/9af955d9-fa29-4d00-b37e-b735b4d33262" />



Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1346" height="637" alt="image" src="https://github.com/user-attachments/assets/c9b6110d-0d16-430b-9983-c9c3cf6f4deb" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
