# Cycle-1-----1-Simulation-of-star-topology-network
# 🖧 Network Simulation using Cisco Packet Tracer

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

| SENDER/RECEIVER | PC0 | PC1 | PC2 | PC3 | PC4 | PC5 |
|------------------|-----|-----|-----|-----|-----|-----|
| PC0              |  ---   |  Success   |  Success   |   Success  |    Success |   Success  |
| PC1              |   Success  |    --- |   Success  |  Success   |  Success   |   Success  |
| PC2              | Success    |  Success   |  ---   |   Success |  Success   |     Success |
| PC3              | Success    |  Success   |    Success |   ---   | Success   |  Success   |
| PC4              |  Success   | Success    |  Success   |  Success   |  ---   |   Success  |
| PC5              |   Success  |    Success |  Success   |   Success  |   Success  |  ---   |

## 🗺️ NETWORK DIAGRAM
---
<img width="1920" height="1080" alt="Screenshot 2026-10-10 110519" src="https://github.com/user-attachments/assets/ede55c6f-3f6d-4238-941b-fbb9f3f4bb73" />


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
<img width="1920" height="1080" alt="Screenshot 2026-10-10 110457" src="https://github.com/user-attachments/assets/382a226d-7827-4b55-a381-6309fa2c1d26" />
<img width="1920" height="1080" alt="Screenshot 2026-10-10 110507" src="https://github.com/user-attachments/assets/098c962a-0c5b-4773-a230-b03c0ab435fc" />

## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified
