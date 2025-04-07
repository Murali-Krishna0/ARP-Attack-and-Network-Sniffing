```

NAME: MURALI KRISHNA S
REG NO: 212223230129

```

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
![430838157-ddf4c952-ee40-4769-b7d5-725b1aed8e2c](https://github.com/user-attachments/assets/7466b792-eafc-41a5-b13a-9207531379c1)
![430838180-418733aa-f3a6-4713-837d-adead14f7aa7](https://github.com/user-attachments/assets/71b14661-2cb1-4288-8551-1b10d53c4427)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![430838206-f9699724-ab99-42d5-bac0-85ca8e3c9b99](https://github.com/user-attachments/assets/9e91b0ea-5dde-4d72-872a-c5a7218a76c3)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![430838248-e35266c5-1b81-44a1-b987-7a99130cb813](https://github.com/user-attachments/assets/7a83aae5-3f91-40d4-aca6-04fadb254b2d)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![430838320-8c1c9fc5-b4d4-448e-97a9-94ac7ab54458](https://github.com/user-attachments/assets/0de33fdd-5fb5-4584-b07e-eb8b77799897)



Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![430838954-c662675c-75b1-451b-91cc-362eb3ac4dd2](https://github.com/user-attachments/assets/55f3ae56-1a60-4f15-a726-963ce6429c6a)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:#

## OUTPUT:



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
