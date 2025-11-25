# ARP-Attack-and-Network-Sniffing
Name: LOGA MITHRA
Reg no: 212223100027
# Explore Network Sniffing and ARP Aacks
# AIM:
To explore network sniffing and ARP Aacks
## STEPS:
### Step 1:
Install kali linux either in paron or virtual box or in live mode
### Step 2:
Invesgate on the various categories of tools as follows:
### Step 3:
Open terminal and try execute some kali linux commands
## ARP Aacks:
ARP spoofing: A hacker sends fake ARP packets that link an aacker's MAC address with an IP of a
computer already on the LAN.
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot 2025-03-28 142215](https://github.com/user-attachments/assets/009f19f2-96c7-41be-b359-2b80025f7c92)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> -r <gateway>
eth0 should replaced by appropriate interface from iconfig command
## OUTPUT:
![VirtualBox_KALI_29_03_2025_08_04_30](https://github.com/user-attachments/assets/419dd68a-70b3-4b4f-8c26-4fa4a018ebae)

Invoke the wireshark and examine the various menus and controls of the tool. Also following shows
how wireshark can be used as sniffing tool.

![VirtualBox_KALI_27_03_2025_05_59_42](https://github.com/user-attachments/assets/bb110185-9543-4625-9851-bc8cce0d5943)

##Eercap
Eercap supports acve and passive dissecon of many protocols (even encrypted ones) and
includes many feature for network and host analysis.
Eercap can be used as sniffing tool as illustrated below:

![VirtualBox_KALI_28_03_2025_15_08_43](https://github.com/user-attachments/assets/26697a8c-9818-4014-b26d-6a179786e97d)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
