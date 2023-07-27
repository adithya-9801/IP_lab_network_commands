# IP_lab_network_commands
ip lab network commands
1. IPCONFIG
IPCONFIG command is used to display the IPv4, IPv6, subnet mask, default Gateway of all the network adapters in the system.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/23edd1c5-3b08-42c2-a089-f95c01995ace)

Sub parameters of ipconfig-
 * IPCONFIG /all --  Similar to IPCONFIG, it provide extra details like DNS Server Address, DHCP Server Address, IP's expiration Period.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/2a398c01-aeb6-467e-ad85-5562850dd5e0)

* IPCONFIG /release -- This command is used to erase the current IP Information for a specified network Adapter.
  ![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/8fc6d9d6-801b-4dd3-a306-975d3535c3f3)

*IPCONFIG /renew -- This command is used to renew the IP Information that is erased using the release command.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/23334e24-82c4-49bc-a52b-8b5cbcb51c38)

*IPCONFIG /displaydns -- This command is used to display the DNS Information of the websites that is stored in the DNS Resolver Cache.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/d74d886a-a1bf-4fe4-ad2c-c31a114f583c)

* IPCONFIG /flushdns -- This command is used to clear or fulsh the DNS Information of the Website that is Stored in the DNS Resolver Cache
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/a9764b73-43b5-4121-bd95-d62c63d540a4)

*IPCONFIG /registerdns -- This command manually registers DNS Record for the specific Network Adapter.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/a7762748-69cb-42b3-bf23-6512f0e4ecda)


2.PING 
PING Command is used to test the reachability of the Host in the IP Network by sending the ICMP Packets.
Parameters of ping:-
 * ping -n :This command is used to test the reachability of the website and including a flag of -n specifies the count of ICMP Packet need to be sent.

* ping -w :This command also serves the same purpose of PING Command, additionally we are adding 3000 ms which specifies the timeout of the packet to drop if there's no reply from the host after the specified time. The Default Value is 1000 millisecond (ie) 1 second

* ping -l : Similar to PING Command,  we are add a flag -l 64 which specifies the size of the ICMP Packets in Bytes. The Default Packet size is 32 Bytes.

* ping -f : Allows fragmentation, mainly used for data loss and checks the receiver's capacity upto which extent it receives the data
 ![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/d6829eec-6c4e-4813-810d-17b384fc57c6)
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/316a42c6-55aa-45f9-9dd7-c7b6d5d9f586)


3. Tracert:
   displays the number of hops/systems between the source and destination (ie) how many devices it traverses during the entire transmission.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/c9857a32-1c31-4809-89d9-626d3fd14959)


4. Nslookup:
   Utilized to obtain information about domain names or IP addresses.
   ![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/19ce4a78-f3ac-47bf-a482-72ac27fa3291)
   
5. Netstat: displays network-related information of a system.
    ![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/19ce4a78-f3ac-47bf-a482-72ac27fa3291)
   Parameters of netstat commands:
*netstat: Displays a list of active connections, both incoming and outgoing.
*netstat -a: Shows all active connections and listening ports.
*netstat -n: Displays numerical addresses and port numbers, instead of resolving them to hostnames.
*netstat -p: Shows the process ID (PID) associated with each network connection.
*netstat -r: Displays the routing table, showing the network routes.
*netstat -s: Provides statistics for various protocols, such as TCP, UDP, IP, and ICMP.
*netstat -e: Displays the detailed information about the network traffic and statistics related to the Ethernet interface.
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/69b5e0f5-a7d6-463d-bd1a-55358f186a5c)
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/99cf7db9-ed53-4cca-bd16-a5fc2d9569e3)
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/71779689-c84b-48d8-82c5-438185e420e0)
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/6efd7c55-0c71-4760-9e72-2924659bfd0b)
![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/b7d5bbab-d961-4aac-a10b-0159b0bf96da)

6. ARP:
 ARP -a:
    Used to view the current ARP (Address Resolution Protocol) cache on a system. ARP is a protocol used to map IP addresses to MAC (Media Access Control) addresses on a local network. The ARP cache stores the associations between IP addresses and MAC addresses for devices on the same network.
   ![image](https://github.com/adithya-9801/IP_lab_network_commands/assets/103358857/c42f28a6-4dcb-4290-b960-4383dd0511f3)










  



