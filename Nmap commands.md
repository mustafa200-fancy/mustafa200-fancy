Scan Network Range : [!bash!]$ sudo nmap 10.129.2.0/24 -sn -oA tnet | grep for | cut -d" " -f5
-sn :	Disables port scanning.
-oA : tnet	Stores the results in all formats starting with the name 'tnet'
-iL :	Performs defined scans against targets in provided 'hosts.lst' list.
-PE	: Performs the ping scan by using 'ICMP Echo requests' against the target.
--reason : Displays the reason for specific result.
--packet-trace : Shows all packets sent and received
-O <IP-ADDRESS> to know what the "os" is runnig on this ip
