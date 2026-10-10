# Cycle-1-----1-Simulation-of-star-topology-network
# 🖧 Network Simulation using Cisco Packet Tracer
## NAME : KESAVAN S
## REG : 212223060125



## 🎯 AIM
To simulate a network with topology using Cisco Packet Tracer and verify connectivity between computers using ICMP.

## 🛠️ EQUIPMENTS REQUIRED
- Desktop Computer  
- Cisco Packet Tracer 5.0 Software

## 📍 IP ASSIGNMENT

| NAME | IP ADDRESS     | SUBNET MASK     | NETWORK     | CLASS   |
|------|----------------|-----------------|-------------|---------|
| PC0  | 192.168.1.10   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC1  | 192.168.1.30   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC2  | 192.168.1.20   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC3  | 192.168.2.20   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC4  | 192.168.2.30   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC5  | 192.168.2.10   | 255.255.255.0   | 192.168.1.2 | Class C |

## ⚙️ PROCEDURE

1. Open Cisco Packet Tracer software.  
2. Drag a 2950 Switch from the toolbar and drop it into the workspace.  
3. Drag a PC terminal from the toolbar and drop it into the workspace.  
4. Repeat Step 3 to add four more terminals.  
5. Select Copper Straight-Through cable and connect each PC to the 2950 switch using different ports.  
6. Click on each PC, select the Fast Ethernet interface, and assign the IP address and subnet mask.  
7. Repeat Step 6 for all PC terminals.  
8. Open the Terminal tab from the Desktop section of each PC and verify connectivity using the `ping` command.  
9. Use “Add Simple PDU” from the toolbar to test connectivity between source and destination PCs.

## 📊 IP CONNECTIVITY TABLE

<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/0fe2e44a-c73f-442f-8582-e2356ae76be6" />



## 🗺️ NETWORK DIAGRAM
---
<img width="1535" height="862" alt="Screenshot 2026-10-10 110226" src="https://github.com/user-attachments/assets/865d8295-6d11-450f-8a33-44118674c565" />



## 🧾 BASIC NETWORKING COMMANDS

## IP Configuration
## IP Configuration Details: 
## (i)	ipconfig Command(windows OS) (or) ifconfig command(Linux OS) Syntax: C:\> ipconfig 
## (ii)	ipconfig/all Command:
## Syntax:
C:\> ipconfig /all 
## Testing Connectivity: 
## (i)	Self Ping Command:
## Syntax:
## c:\> ping <ipaddress> Example:
## C:\> ping 172.17.80.201
## C:\> ping 127.0.0.1 (ii) Ping to Destination Syntax:
## c:\> ping <destination-ipaddress> Example:
## C:\ping 172.17.80.1
## To Display IP to Physical address Translation Table and trace the route
## i) Arp Command Syntax:
 
## C:\arp –a
## (ii)	To trace the route Syntax:
## C:\tracert <ipaddress (or) specific address> Example: C:\tracert 172.17.80.1
## C:\tracert www.saveetha.ac.in

## OUTPUT
---
<img width="1533" height="857" alt="Screenshot 2026-10-10 110253" src="https://github.com/user-attachments/assets/2b252d77-ad1e-4101-a541-58dd91e315e8" />


## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified
