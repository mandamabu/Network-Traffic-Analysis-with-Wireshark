# Network-Traffic-Analysis-with-Wireshark
A network traffic analysis project using Wireshark and tcpdump on Kali Linux. The project analyzes HTTP,DNS and ARP traffic, includes annoted PCAP files, a suspicious traffic analysis report and a Wireshark Filter Cheat Sheet.

# Tools Used
Kali Linux
A Linux distribution used as the primary operating system for capturing and analyzing network traffic.
Wireshark
A network protocol analyzer used to capture, inspect, and filter network packets.
VirtualBox
A virtualization tool that was used to host the Kali Linux virtual machine used in this project.
Host-Only Adapter
A VirtualBox networking mode that creates a private network in a controlled environment without requiring internet access.

## Project Steps
1. Configured a Host-Only Adapter in VirtualBox to create an isolated network environment.
2. Started packet capture on the host-only network interface (eth0).
3. Generated network traffic for HTTP filter and downloaded sample captures for DNS and ARP anlysis.
4. Examined HTTP GET requests and identified the Request method, Host header, User-Agent, and response code.
5. Analyzed DNS queries and responses to observe domain name resolution.
6. Investigated ARP Requests and Replies, noting source and destination MAC addresses.
7. Used tcpdump from the command line to capture network traffic and save it as a PCAP file.
8. Opened and analyzed the captured PCAP files in Wireshark.
9. Documented observations and created a Suspicious Traffic Analysis Report.
10. Developed a Wireshark Display Filter Cheat Sheet containing commonly used filters and their functions.
    
